# novaMERNbackend

## Description
MERN application built to understand the backend structure and applications needed to communicate with the database and communicate with the frontend. This website enables users to see share places and login to share places and their location and image. The contents of the website that a user sees and shares were stored in MongoDB with the help of Express and Mongoose to simplify the communication with MongoDB database and create solid structures for places and users separately.

## Setup
* Created a folder with a simple Node Express Application 
* Then Established a connection with MongoDB
```console
npm install --save mongodb
```
* Retrieved Connection String from MongoDB database to establish a connection method with Node.js
```js
const url = 'mongodb+srv://<user>:<password>@cluster0<mongodb.net>/<collection>?<retryWrites>'
```
* Used Schemas to define the structures of the documents to be used with MongoDB database
```console
npm install --save mongoose
```
* Encoded Data for Keys and User Credentials using JWT Tokens
```console
npm install --save jsonwebtoken
```

--In Progress

## Credentials
A Nodemon.json file was created to store the credentials used for the Database and API
* Database Username
* Database Password
* GOOGLE API KEY
* JWT KEY
