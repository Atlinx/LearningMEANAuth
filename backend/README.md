# Backend

This is the backend to the app.

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

## Unit Testing

Unit testing is done with ts-node and jasmine. To perform all tests, run

```bash
> npm test
```