# Express-Server-AuthAPI
## Micro-Task #1
It returns a token for sign-up and sign-in.

## Installation
```bash
git clone https://github.com/Ritam02-cyber/Express-Server-AuthAPI.git
```
### Navigation
```bash
cd AuthAPI/
```

### Installation
```bash
npm init
```
Then install the dependencies - express, mongoose, nodemon, dotenv, jsonwebtoken, bcrypt, validator using :-
```bash
npm i
```

Create a .env file and add the MongoDB database username and password :-
```bash
DATABASE_URL = mongodb+srv://<username>:<password>@cluster0.nv6infp.mongodb.net/test
JWT_TOKEN = stringforjwt
```

### Run server
```bash
npm start
```

## API Reference
### Sign-up
It returns a token.
```bash
POST http://localhost:3000/api/sign-up
```

| Parameter | Type | Description |
| :---: | :---: | :---:|
| body | email | required |
| body | password | required |

### Sign-in
It returns a token.
```bash
GET http://localhost:3000/api/sign-in
```

| Parameter | Type | Description |
| :---: | :---: | :---:|
| body | email | required |
| body | password | required |

AuthAPI micros :- https://web.deta.sh/home/ritam02-cyber/default/micros/AuthAPI<br>
Deta server :- https://rf1qzv.deta.dev/
## Author
-[@Ritam02-cyber](https://github.com/Ritam02-cyber)
