# Loan_Status_ML_Model

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

