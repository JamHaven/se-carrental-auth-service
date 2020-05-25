# Car Rental Authentication Microservice

Car Rental microservice project for Service Engineering

## Build and Run 

1. `mvn package`
2. `docker build -t se-carrental/authentication-service .`
3. `docker tag se-carrental/authentication-service rabbitcarrental.azurecr.io/se-carrental/authentication-service:latest`
4. `docker login rabbitcarrental.azurecr.io`
5. `docker push rabbitcarrental.azurecr.io/se-carrental/authentication-service:latest`
6. `docker logout rabbitcarrental.azurecr.io`
7. `docker run -p 2222:2222 se-carrental/authentication-service`

