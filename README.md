# Swagger-UI Command(MUST COPY FROM RAW, ELSE \\" WILL BE REPLACED BY "):
docker run -p 82:8080 -e URLS="[{name:\"GRAVITY-ACCOUNT\", url:\"http://192.168.0.158:8082/gravity-account.yaml\"}, {name:\"GRAVITY-EXAMCONFIG\", url:\"http://192.168.0.158:8082/gravity-examconfig.yaml\"}, {name:\"GRAVITY-EXAMSTATION\", url:\"http://192.168.0.158:8082/gravity-examstation.yaml\"}]" swaggerapi/swagger-ui
