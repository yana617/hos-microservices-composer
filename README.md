# hos-microservices-composer

Composer service for two separate microservices

To test both services locally:
- create compose file
```
touch docker-compose-home.yaml
```
- copy docker-compose.yaml file and change paths to the services
- run start command
```
docker-compose -f docker-compose-home.yaml up --build
```