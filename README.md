# MERN-Docker

This is a boilerplate on the dockerize MERN stack, which includes a React frontend, an Express Backend, and a MongoDB. Running in one docker container.

In this demo, I just created the docker wrapper for the application. The code is based on the [MERN-Stack-CRUD](https://github.com/CodAffection/MERN-Stack-CRUD) by CodAffection. The application demonstrates the end-to-end CRUD (create, read, update, and delete) functionality.

## Demo
![Demo](Demo.gif)

## Run the demo

1. Install [Docker](https://docs.docker.com/get-docker/) 

2. Run the follow command in command prompt
```
$ git clone https://github.com/winstonma/MERN-Docker.git
$ cd MERN-Docker
$ docker-compose up
```

3. Open browser and goto <http://localhost:80>

4. (Optional) You can access API server by opening the browser and goto <http://localhost:4000> (e.g. <http://localhost:4000/postmessages/>)

5. (Optional) You can access database content by accessing `mongodb://localhost:27017` using a MongoDB client (e.g. [Mongo Compass](https://www.mongodb.com/products/compass))

Please execute `docker-compose down` in the command prompt to stop the demo
