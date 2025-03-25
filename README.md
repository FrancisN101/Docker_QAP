This project is a RESTful API for managing a golf club’s members and tournaments. It allows users to add and retrieve members, create tournaments, assign members to tournaments, and perform advanced searches. The API is built using Spring Boot, with data persistence handled by MySQL. The application is containerized using Docker for easy setup and deployment.
It also involves creating a docker configuration(dockerfile and docker-compose.yml) ensuring that MySQL runs in docker as well as testing endpoints using postman to verify that adding, retrieving members, tournaments, and adding members to tournament as well as search functionality are effectively working as expected.

To run the project:
1. Build the spring boot JAR file; by running maven clean, package
2. Build the docker image using dockerfile
3. Start the spring boot and MySQL containers; run docker-compose up
4. Verify that the API is running at localhost:8088 as specified
5. MySQL running in the docker accessible at localhost:3307 as specified
