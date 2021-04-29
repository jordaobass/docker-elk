# ELK pré-configurado (Elasticsearch, logstash e Kibana) 
Orquestração ELK usando docker e docker-compose.

**Configurar**
Basta clonar este repositório e alterar [esta linha de código] (https://github.com/jordaobass/elk-compose/blob/master/docker-compose.yml#L29) para ser
seu diretório de log.

A sincronização do log é feita pelo Filbeat e a configuração é permitida pelo [arquivo de configuração] (https://github.com/waldemarnt/elk-compose/blob/master/filebeat/filebeat.yml), 
apenas mude os prospectores para ler seus próprios arquivos de log.

Você só precisará do docker e do docker-compose para executar este ELK.

** Executando docker-compose: **

`` `docker-compose up```
