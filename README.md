# EyeRest

This is a simple application written with Flask that reminds you to look away from the screen every *x* minutes by playing music.

To start the application run the following command:

```bash
flask run
```

To start it with docker:

```bash
docker build .
docker run -ti --network="host" -p 8081:8081 flaskapp:latest
```

