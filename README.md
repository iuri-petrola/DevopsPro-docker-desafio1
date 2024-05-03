# DevopsPro-docker-desafio1
Repositorio criado para o curso Devops Pro 2.0

# Desafio docker primeiro passos

Desafio 01 - Banco de Dados PostgreSQL
# Resposta: docker run -d --name postgres -p 5432:5432 -e POSTGRES_DB=curso_docker -e POSTGRES_USER=docker_usr -e POSTGRES_PASSWORD=docker_pwd  postgres

Desafio 02 - Banco de Dados MySQL
# Resposta: docker run -d --name mysql -p 3306:3306 -e MYSQL_DATABASE=docker_db -e MYSQL_USER=docker_usr -e MYSQL_PASSWORD=docker_pwd mysql

Desafio 03 - Banco de Dados MongoDB
# Resposta: docker run -d --name mongo -p 27017:27017 -e MONGO_INITDB_ROOT_USERNAME=mongo_usr -e MONGO_INITDB_ROOT_PASSWORD=mongo_pwd mongo
