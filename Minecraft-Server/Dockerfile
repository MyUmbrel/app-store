FROM openjdk:17-jdk-alpine
WORKDIR /minecraft
EXPOSE 25565
COPY . .
CMD java -Xmx1024M -Xms1024M -jar server.jar nogui
