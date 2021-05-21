#Creating Spring Boot Container on Docker

https://www.section.io/engineering-education/spring-docker/

> run create container - 
> docker build --build-arg JAR_FILE=build/libs/\*.jar -t spring-boot-docker:latest .

> list containers - docker image ls

> docker run --name spring-boot-docker -d -p 8080:8080 spring-boot-docker:latest