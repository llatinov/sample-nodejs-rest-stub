# sample-nodejs-rest-stub #

Code examples for following post:

* <a href="https://automationrhapsody.com/build-rest-api-express-node-js-run-docker/">Build a REST API with Express on Node.js and run it on Docker</a>

## Install ##
* Install <a href="https://nodejs.org/en/download/" target="_blank">Node.js</a>
* Open cmd.exe and navigate to project's folder.
* Install project dependencies with following command

`npm install`

## Run ##
Run project with following command

`npm start`

## Functionalities ##

There are several functionalities implemented in the stub. See linked posts for more details how to use them.

### Persons ###

Database where you can add, get or remove persons with JSON showing RESTful web services functionality described in blog post. GET endpoints are: http://localhost:3000/person/all, http://localhost:3000/person/get/{id}, http://localhost:3000/person/remove. POST endpoint is: http://localhost:3000/person/save.

### Version ###

http://localhost:3000/api/version returns a configuration value that is read from external config file.
