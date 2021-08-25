## Spring Boot WebSocket Chat Appplication

## Requirements

1. Java - 1.11.x

2. Maven - 3.x.x

## Steps to Setup

**1. Clone the application**

```bash
git clone https://github.com/abKrazy/spring-boot-websocket-chat-docker.git
```

**2. Build and run the app using maven**

```bash
cd spring-boot-websocket-chat-demo
mvn package
java -jar target/websocket-demo-0.0.1-SNAPSHOT.jar
```

Alternatively, you can run the app directly without packaging it like so -

```bash
mvn spring-boot:run
```

**3. Run as a docker container
docker build -t spring-boot-websocket-chat-demo .

docker run -p 5000:8080 spring-boot-websocket-chat-demo
