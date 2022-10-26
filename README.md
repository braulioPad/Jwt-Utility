# JWT utilities

## Overview 
 Json Web Token demostration using Springboot Security.
 
## API
 ```json
 
 POST /authenticate
 
 Request body:
{
    "user":"javainuse",
    "password":"",
    "api":"api01"
}

Response body:
{
  "jwttoken": ""
}


GET /hello

Auth Header: 
{
  "Authorization": "Bearer <JWT_TOKEN>"
}
 ``` 
 
 
 
 ## Test Credential 
 
 - user: `javainuse`
 - api: `api01`
 - password: `password`


## Instructions to Run this project

Make sure you have Java 8 and Maven installed

Run the project
$ mvn spring-boot:run

server:
  port: 8080
