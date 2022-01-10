# Backend

This is the backend to the app.

It's built with NodeJS, Express, and MongoDB.

It includes authentication and fetching of 

## Starting the Backend

### Docker

To build and run the backend in docker, call

```bash
> docker-compose up --build
```

To just run the backend in docker, call

```bash
> docker-compose up
```

### Node

To build and run the backend using nodejs, call

```bash
> npm run build-start
```

To just run the backend using nodejs, call

```bash
> npm start
```

## Monitoring MongoDB

I used MongoDB Compass to monitor the database. If you are running the backend from NodeJS, then you can connect to `localhost:27017` in compass. If you are running the backend from docker, then you can connect to `localhost:27018` in compass. Don't forget to input the username and password found in the `.env` file when you are connecting in compass.

## Unit Testing

Unit testing is done with ts-node and jasmine. To perform all tests, run

```bash
> npm test
```