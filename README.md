# POC utilizando o pgloader
Migrando dados do MYSQL para o POSTGRESQL

**Setup**

1. Executar `docker-compose up -d`

2. Para executar a migração da base todas :  `./pgloader_migrate.sh`

3. Para executar a migração de algumas tabelas, segundo o arquivos de configuração :  `bash table.sh`
