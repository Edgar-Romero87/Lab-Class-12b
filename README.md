# Lab-Class-12b
LAB: OAuth

## Author: Edgar Romero

## Links and Resources

ci/cd (GitHub Actions)
back-end server url (when applicable)
front-end application (when applicable)

## Setup

.env requirements (where applicable)

i.e.

PORT - 3000
MONGODB_URI - mongodb://localhost:27017/auth

### Dependencies:
```
@code-fellows/supergoose": "^1.0.11",
   "base-64": "^0.1.0",
    "bcrypt": "^5.0.0",
    "dotenv": "^8.2.0",
    "express": "^4.17.1",
    "jsonwebtoken": "^8.5.1",
    "mongoose": "^5.10.5"
```
## How to initialize/run your application (where applicable)

e.g. npm start
## How to use your library (where applicable)

## Tests

Use `nodemon` on the terminal  to turn on the server.

## UML

Link to an image of the UML for your application and response to events



## Changelog 

- 2020-Sep-10: Authentication System Phase 1: Deploy an Express server that implements Basic Authentication, with `signup` and `signin` capabilities, using a Mongo database for storage.

- 20202-Sep-19: New requirement is that any user with a valid token (retrieved from either Basic Authentication or OAuth) is able to use that token to login to the system and potentially access protected routes.

- 2020-Sep-20: we’ll be integrating with GitHub’s OAuth service to provide a way for users to easily `signup` and `signin` to our system in addition to the Basic Authentication we’ve already built.
