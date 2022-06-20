# Bubber Diner

- [Bubber Dinner Api](#bubber-dinner-api)
  - [Auth](#auth)
    - [Register](#register)
      - [Register Request](#register-request)
      - [Register Response](#register-response)
    - [Login](#login)
      - [Login Request](#login-request)
      - [Login Response](#login-response)


## Auth

### Register
```js
POST {{host}}/auth/register
```

#### Register Request
```json
{
  "firstName" : "sajjad",
  "lastName" : "golcohin",
  "email": "sajjad.gol@gmail.com",
  "password" : "123456"
}
```
#### Register Response
```js
200 Ok
```

### Login