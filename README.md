# Prática engenheiro de dados
- Participante: César Noronha
- Email: cesarsnoronha@gmail.com

## Arquivos nesse repositório:
- main.ipynb 
    - Nesse arquivo estão as perguntas e os códigos com as respostas para todos as perguntas em formato de célula.
- environment.yml
    - Neste arquivo estão os as bibliotecas necessários para executar o arquivo main.ipynb. Você pode criar um ambiente virtual seguntos as instruções do setup ou instalar as bibliotecas individualmente através do pip. Note porém que só é possível se conectar ao BigQuery caso você não esteja utilizando um ambiente virtual, e sim o da própria máquina.
- arquivos.csv
    - Nestes arquivos estão os dataframes em formato csv gerados em algumas etapas do processamento. Esses arquivos foram feitos inicialmente para facilitar obter os dataframes no meio do projeto, mas deixei no arquivos para salvar tempo de processamento no teste. O arquivo que contem o dataframe final é o df_from_sql.csv
- .gitignore
    - Arquivo usado para excluir o service account do github. Para executar o código principal será necessário adicionar o service account à pasta do arquivo main.ipynb


## Setup

- Como instalar as bibliotecas?
    - Rodando da própria máquina:
        instale as bibliotecas atraves do pip install no terminal


    - Ambiente virtual       * O BigQuery não funciona aqui
        - Rodar no terminal:
            conda env create environment.yml 
            conda activate environment.yml 

        - Em caso de problemas:
            conda deactivate
            conda env remove -n .env_requests-venv
            
            Caso aconteça algum erro:
            conda env update environment.yml 

- Após instalacão das bilbiotecas colocar o service account na pasta do arquivo, e sen seguida rodar o comando:
    set GOOGLE_APPLICATION_CREDENTIALS=Users/Cesar-mac/Desktop/aplicacao_be_growth/svc-data-engineer-test.json


