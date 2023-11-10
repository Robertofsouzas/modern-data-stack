# airbyte-dbt-airflow-snowflake-metabase
Repositório para armazenar os artefatos do Pipeline utilizando Modern Data Stack com AirByte + DBT + Airflow + SnowFlake + Power BI


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

- No Airbyte (Destination Loading Method):x

    - Local Staging (Ambiente de Desenvolvimento)x
    - Cloud Staging (Ambiente de Produção)x


Transformação:

- No Dbt:

    - Criação da Conta x
    - Conexão com o Github x
    - Criação do Dbt Project x
    - Criação do Profile de conexão com o snowflake x
    - Criação do Schema x
    - Criação dos Modelos Base x
    - Criação do Modelo Relacionado x
    - Visualização gráfica do modelo  x
    - Teste de execução x
    - Commits, Branches, Pull Requests, Merges no Github  x
    - Obtenção do link de conexão com o Airbyte  x


Visualização:

- No PowerBI:

    - Conectar Power BI com o Snowflake 
    - Criar uma Question  
    - Criar um Dashboard 
    


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
	
