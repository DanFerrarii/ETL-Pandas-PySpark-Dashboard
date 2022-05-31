# ETL-Pandas-PySpark-Dashboard

Projeto individual desenvolvido no curso de Engenharia de dados na SoulCode Academy

## Diretrizes a serem seguidas:

*Nivel Infra*
* O Dataset deve ser salvo em ambiente cloud (Cloud Storage)
* O arquivo original e tratado deve ser salvo em MongoDB Atlas em coleções diferentes
* Os DataFrames devem ser obrigatoriamente salvos em uma bucket do CloudStorage

*Nivel Pandas*
* O arquivo está em outra linguagem e deve ter seus dados traduzidos para Português-BR
* Realizar a extração corretamente para um dataframe
* Verificar a existência de dados inconsistentes e realizar a limpeza para NaN ou NA
* Realizar o drop(se necessário) de colunas do dataframe realizando o comentário do porque da exclusão 
* Todos os passos devem ser comentados

*Nivel PySpark*
* Deverá ser montada a estrutura do DataFrame utilizando o StructType.
* Realizar a mudança de nome de pelo menos 2 colunas
* Deverá criar pelo menos duas novas colunas contendo alguma informação relevante sobre as outras colunas já existentes (Funções de Agrupamento, Agregação ou Joins).
* Deverá utilizar filtros, ordenação e agrupamento, trazendo dados relevantes para o negócio em questão. 
* Utilizar pelo menos duas Window Functions

*Nivel SparkSQL*
* Utilizar no minimo 5 consultas diferentes utilizando o SparkSQL, comentando o porquê de ter escolhido essas funções e explicando o que cada consulta faz.

*Nível DataStudio*
* Construir um dashboard (maximo 1 pagina) para apresentação dos insights

*Ferramentas*\
Colab ou Ides | Google Cloud | Data Studio

