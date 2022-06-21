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

```js
{
  "id" : "abd-asdas2-23232ggs",
  "firstName": "sajjad",
  "lastName": "golchin",
  "email": "sajjad.gol@gmail.com",
  "token" : "lajsdlkjaskdjalksjdalksd"
}
```

### Login

```js
POST {host}/auth/login
```