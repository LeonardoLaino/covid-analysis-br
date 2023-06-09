# covid-analysis-br
Projeto que visa analisar e extrair conhecimento dos dados de como foram os anos de pandemia no Brasil.

* Os dados utilizados neste estudado são provenientes da Universidade de John Hopkins, que por sua vez realizou um excelente trabalho durante os anos de pandemia coletando e analisando dados acerca deste assunto.
___

# v0.1 - Development

* Criação da Branch Development

* Adicionado um arquivo raw já filtrado somente com dados referentes ao Brasil e com as colunas que não serão utilizadas já removidas. Essa adição serve para casos em que o Kernel necessite ser resetado, não haja a obrigação de extrair os dados novamente (o processo leva ~3.5 minutos).
    * O arquivo foi salvo em Pickle (`.pkl`)

* Finalizada a parte de extração de dados

* Iniciado a parte de Data Wrangling
____


# v0.2 - Development

* Continuação do Data Wrangling (dados dos casos)

* Adicionado célula para importar os dados no formato .pkl
___


# v0.3 - Development 

* Término do Data Wrangling (dados dos casos)

* Export dos dados manipulados dos casos para .csv (`file: covid-cases-wrangled.csv`)
___

# v0.4 - Development (Current)

* Término do Data Wrangling (dados de vacinação)

* Export dos dados manipulados das vacinas para .csv (`file: vaccines-wrangled.csv`)
___


# (Future/Next)

* Transformar a seção de Data Extraction dos dados de casos em um script .py

* Iniciar seção dos dados de vacinação.

* Iniciar ETL dos dados de vacinação.

* Merge com a main

* Criar dashboard no Google Data Studio