create package.json

{
  "name": "jwtAuthNodeApi",
  "main": "server.js"
}

install packages

npm install express body-parser morgan mongoose jsonwebtoken --save

- express is the popular Node framework
- mongoose is how we interact with our MongoDB database
- morgan will log requests to the console so we can see what is happening
- body-parser will let us get parameters from our POST requests
- jsonwebtoken is how we create and verify our JSON Web Tokens