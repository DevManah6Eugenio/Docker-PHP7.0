# Docker-PHP7.0
Contêiner Docker com serviço Web Apache2, PHP7.0 e banco de dados MySQL 

-------------------------------------------------------------------------------------------------
Para iniciar os contêineres de aplicação e banco de dados, executasse o comando abaixo.
 
docker-compose up -d --build

-------------------------------------------------------------------------------------------------  
Para acessar o MySQL diretamente no contêiner com o comando

docker exec -it mysql_container mysql -p

Obs.: a senha do banco se não foi alterado do arquivo docker-compose.yml, é "senha".
