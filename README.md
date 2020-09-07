Notes

docker run --name todo-app -e POSTGRES_PASSWORD=123456 -p 5432:5432 -d postgres

docker stop <name> docker start <name>
docker ps

mvn clean package
mvn spring-boot:run