# SpringBootDocker
# A Sample that build a Hello World Spring Boot app and creates a docker image of the code
# once you clone the app 
# 1. gradle build
# 2. docker build --build-arg JAR_FILE=build/libs/*.jar springboot-sample/spring-boot-sample-docker
# 3. docker run springboot-sample/spring-boot-sample-docker
# 4  go to localhost:8080 to see that your docker container running with Springboot app
