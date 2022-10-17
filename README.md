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
  "Authorization": "Bearer AuthTOKEN"
}
 ``` 
 
 
 
 ## Test Credential 
 
 - user: `javainuse`
 - api: `api01`

