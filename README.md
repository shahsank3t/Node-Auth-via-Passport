# Node-Auth-via-Passport
Authentication and Authorization using Passport for local, google, facebook and twitter accounts

Step:
To install the dependencies, run the command:
	npm install

To start the server, run the command:
	node server.js
(This will run the server on port: 8080)

Go to browser and visit URL: http://localhost:8080

Note:
For Google / Facebook / Twitter login authentication, one needs to create an application and save their credentials in config/auth.js file.

Stack:
Express 4.0
MongoDB
Node
EJS Templating Engine (can be changed to JADE in near future)
Passport

Currently Working:
1. Local Signup and Login
2. Google Login

Issues:
1. From Google login, currently information shown is not appropriate.