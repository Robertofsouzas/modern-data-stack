# airbyte-dbt-airflow-snowflake-metabase
Repositório para armazenar os artefatos do Pipeline utilizando Modern Data Stack com AirByte + DBT + Airflow + SnowFlake + Metabase


Tarefas:

Infraestrutura:

- Setup do ambiente de desenvolvimento (Hardware, Software - Linux, Python, Docker, Curl, Pip, Git, Npm, etc...) X

- Setar as Permissoes do Gitpod ao Repositorio no Github X

- Subir o Airbyte via docker x

- Subir o Airflow via docker x

- Subir o Metabase via docker = substituie pelo Power BI

- Criar o script de execução 

- Testar a Execução 

- Snowflake Data Warehouse:x
    
    - Criar a Conta no SnowFlake x
    - Verificar a existência das tabelas x
    - Obter os links de conexão e nome da conta x


Extração:

- No Airbyte:

    - Conectar com as origens baseadas nos Csvs x
    - Criar as entidades no snowflake através do script base da documentação    x
    - Conectar o destino no snowflake x
    - Criar as conexões do airbyte associando as origens ao destino x
    - Testar as conexões x


Preparação:

- No Airbyte (Destination Loading Method):

    - Local Staging (Ambiente de Desenvolvimento)x
    - Cloud Staging (Ambiente de Produção)x


Transformação:

- No Dbt:

    - Criação da Conta 
    - Conexão com o Github 
    - Criação do Dbt Project 
    - Criação do Profile de conexão com o snowflake 
    - Criação do Schema 
    - Criação dos Modelos Base 
    - Criação do Modelo Relacionado 
    - Visualização gráfica do modelo  
    - Teste de execução 
    - Commits, Branches, Pull Requests, Merges no Github  
    - Obtenção do link de conexão com o Airbyte  


Visualização:

- No Metabase:

    - Conectar Metabase com o Snowflake 
    - Criar uma Question  
    - Criar um Dashboard 
    - Adicionar uma Question 
    - Visualizar o Resultado  


Orquestração:

- No Airflow:

    - Criar a dag  

    - Criar a Docker network

    - Incluir nos composes a network criada

    - Setup Up no serviço

    - Testar a conexao entre os containers do airflow e do airbyte

    - Criar as conexões com o Airbyte através do script  

    - Testar a execução do pipeline  


Encerramento:

- Material de Apoio:

    - Links 

    - Códigos fonte

    - Apresentação
	