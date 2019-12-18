# Swagger-UI Command(MUST COPY FROM RAW, ELSE \\" WILL BE REPLACED BY "):
## DEV
docker run -p 83:8080 -e URLS="[{name:\"GRAVITY-ACCOUNT\", url:\"http://192.168.0.158:8082/gravity-account.yaml\"}, {name:\"GRAVITY-EXAMCONFIG\", url:\"http://192.168.0.158:8082/gravity-examconfig.yaml\"}, {name:\"GRAVITY-EXAMSTATION\", url:\"http://192.168.0.158:8082/gravity-examstation.yaml\"}]" swaggerapi/swagger-ui
## PROD
docker run -p 93:8080 -e URLS="[{name:\"GRAVITY-ACCOUNT\", url:\"http://192.168.0.158:8092/gravity-account.yaml\"}, {name:\"GRAVITY-EXAMCONFIG\", url:\"http://192.168.0.158:8092/gravity-examconfig.yaml\"}, {name:\"GRAVITY-EXAMSTATION\", url:\"http://192.168.0.158:8092/gravity-examstation.yaml\"}]" swaggerapi/swagger-ui
