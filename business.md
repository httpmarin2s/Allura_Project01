## Entendimento do Negócio
**CEAPS contém todos os gastos que senadores brasileiros declararam, divididos por ano**.
Anos que estarei baseando a minha análise.[2022, 2021, 2020, 2019,2018]


---

### Tipos de dados fonecidos

- 'ANO', Quantitativa; Discreta; inteiro
- 'MES', Quantitativa; Discreta; inteiro
- 'SENADOR', Qualitativa; Nominal; Objeto
- 'TIPO_DESPESA', Qualitativa; Nominal; Objeto
- 'CNPJ_CPF', Qualitastivas; Nominais; String
- 'FORNECEDOR',Qualitativa; Nominal; Objeto
- 'DOCUMENTO', Qualitastivas; Nominais; String
- 'DATA', Quantitativa; Discreta; inteiro
- 'DETALHAMENTO', Qualitastivas; Nominais; String
- 'VALOR_REEMBOLSADO',Quantitativa; Contínua; Float
- 'COD_DOCUMENTO' Qualitastivas; Nominal; Inteiro

1. Tempos um total de 93848 linhas e 11 colunas
2. Temos os seguintes tipos de dados: 
    
    ANO                   int64 🟢
    MES                   int64 🟢
    SENADOR              object 🟢
    TIPO_DESPESA         object 🟢
    CNPJ_CPF             object 🟢
    FORNECEDOR           object 🟢
    DOCUMENTO            object 🟢
    DATA                 object 🔴 → precisa trocar o tipo para datatime
    DETALHAMENTO         object 🟢
    VALOR_REEMBOLSADO    object 🟢
    COD_DOCUMENTO         int64 🟢
    
3. Não temos valores duplicados 
4. Porém temos alguns valores ausentes: 
    1. DOCUMENTO             3979
    2. DETALHAMENTO         36383
5. Qual seria a melhor forma de tratar esses valores?
    1. descartar apenas os valores ausentes e manter os dados no conjunto
    2. eliminar o recurso (a coluna inteira) por atacado porque há tantos pontos de dados ausentes que não é adequado para análise.
