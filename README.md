# Teste para engenheiro de dados 
- Participante: César Noronha
- data de entrega: 30/12/2022

## Arquivos nesse repositório:
- main.ipynb 
    - Nesse arquivo estão as perguntas e os códigos com as respostas para todos as perguntas em formato de célula.
- environment.yml
    - Neste arquivo estão os as bibliotecas necessários para executar o arquivo main.ipynb. Você pode criar um ambiente virtual seguntos as instruções do setup ou instalar as bibliotecas individualmente através do pip. Note porém que só é possível se conectar ao BigQuery caso você não esteja utilizando um ambiente virtual, e sim o da própria máquina.
- arquivos.csv
    - Nestes arquivos estão os dataframes em formato csv gerados em algumas etapas do processamento. Esses arquivos foram feitos inicialmente para facilitar obter os dataframes no meio do projeto, mas deixei no arquivos para salvar tempo de processamento no teste. O arquivo que contem o dataframe final é o df_from_sql.csv
- .gitignore
    - Arquivo usado para excluir o service account do github. Para executar o código principal será necessário adicionar o service account a parta do arquivo main.ipynb


## Setup

- Como instalar as bibliotecas?
    Rodar no terminal:
    conda env create environment.yml 
    conda activate environment.yml 

    conda deactivate
    conda env remove -n .env_requests-venv
    
    Caso aconteça algum erro:
    conda env update environment.yml 


set GOOGLE_APPLICATION_CREDENTIALS=Users/Cesar-mac/Desktop/aplicacao_be_growth/svc-data-engineer-test.json

## Sobre o projeto

## Integrantes

    César Augusto Noronha
## Organização do projeto

- Onde estão as bases de dados?
    datasets/raw/train_u6...
- Tem dados processados? Onde?
    Os dados são processados na criação de cada gráfico, pois alguns dados precisam de formatos diferentes.
- Onde estão os Notebooks com as Análises Exploratórias?
    report.ipynb
- Onde está o Notebook com as comparações entre modelos?
    report.ipynb


- Como baixar os dados?
    Os dados estão no arquivo Projeto_analise_credito/main/datasets/raw/train_u6lujuX_CVtuZ9i.csv
    e podem ser baixados com a função:
    df = pd.read_csv('../datasets/raw/train_u6lujuX_CVtuZ9i.csv')

- Onde armazenar a base de dados?
    Em uma pasta na área de trabalho

