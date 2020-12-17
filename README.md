# spring-cloud


./mvnw clean package -DskipTests
az spring-cloud app deploy -n todo-gateway --jar-path target/demo-0.0.1-SNAPSHOT.jar

Check Logs : 
az spring-cloud app logs -n todo-service -f