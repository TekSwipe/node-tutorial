## Download the node-modules 

Before you can start, you will have to first download the node modules by running this in the code in the command line

```shell
npm i
```

## Setting up .env variables

You will have to configure a server with mongoDB for this app to work

first create a file and call it ``` .env ``` in the main directory

then add these .env variables in the .env file

```env
MONGO_USERNAME=<your user name>
MONGO_PASSWORD=<your password>
MONGO_SERVER=<your mongo server>
```

## Running the app with nodemon

Install nodemon for instant server restarts

```shell
npm i nodemon -g
```
Once you have nodemon, just run the following command

```shell
npm run dev
```

Alternativly, you can run it with nodemon itself from the command line

```shell
nodemon app.js
```
## Running the app with just node

If you don't want to run nodemon, you can just run it with node

```shell
node app
```

