FROM openjdk:11

WORKDIR /app/jmusicbot
COPY bot.jar .
COPY config.txt .

ENTRYPOINT [ "java", "-Dnogui=true", "-jar", "bot.jar" ]