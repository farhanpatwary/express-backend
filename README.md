# Express Backend
This is a Express.js Backend template, it contains most of the boilerplate code to start an Express.js Project.  
It allows for User Authentication using JSON Web tokens. 
## Usage
To use this, clone or download and create a .env file as such:
```PORT=8000
DB_URL=
DB_URL_TEST=
SECRET=
```
Where:
* PORT is the HTTP port to be used by the server
* DB_URL is the MongoDB connection string
* DB_URL_TEST is the MongoDB connection string for your test database 
* SECRET is the secret used when generating JSON Web tokens for authentication  
## About
This repository was made by taking any reusable code from [Giraffe](https://github.com/farhanpatwary/giraffe-back-end).  
This allowed me to create [Card](https://github.com/farhanpatwary/card) without having to rewrite a lot of code.
