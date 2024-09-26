Projeto da Semana Ciência de Dados Alura
1. Introdução
Estou participando da Semana de Ciência de Dados da Alura, em que consiste em uma série de desafios práticos que abordam Ciência de Dados. O primeiro Desafio envolveu uma abordagem de tratamento de Dados e com ele eu aprendi muitas coisas, que ficará na aba de ensinamentos.

2. Escopo do Projeto
O Objetivo do projeto era pegar dados das despesas CEAPS e tratar eles, e para isso adotei a seguinte verificação:

Verificar valores ausentes (NaN)
Remover Duplicatas
Conferir Tipos de Dados
Tratar Outliers
Padronizar valores categóricos
Formatar Colunas de Data
Remover Colunas Irrelevantes
3. Metodologia
Para esse projeto utilizei muito a biblioteca pandas, aprendi muitas coisas realcionado a esse projeto justamente por explorar tudo que ele tinha a me oferecer. Entretanto, para realizar esse tratamento de dados tive alguns desafios.

4. Problemas
Tive problemas e desafios durante o projeto e isso me mostra o quanto que a profissão de ciência de dados deve ser valorizada, as bases vem com muitas especificidades e nem sempre vão estar em um padrão de fácil modelagem.

Problema	Dificuldade	Tratamento	Solucionado?
Caracteres em Latim e delimitado por ;	Baixa	encoding='latin1', delimiter=';'	Sim
Unir todos os dataframes em um só	Baixa	pd.concat	Sim
Verificar valores duplicados	Baixa	df_completo.duplicated().sum()	Sim
Conversão de Tipos de Dados	Muito altos	Não realizado	Não
5. Lições aprendidas
Meu maior problema foi a conversão de dados para os tipos adequados. O ideal em qualquer conversão de dados é você ter uma abordagem de backup, de modo que conversões, exclusão de colunas e etc devem ser feitos em uma base reserva. E é isso que irei abordar em minhas análises futuras.

6. Considerações Finais
Esse projeto me fez explorar aspectos dos pandas completamente desconhecidos para mim, aprendi a concatear dataframes em um único arquivo e também a como realizar limpezas de uma maneira mais adequada.

Observações:
