Modify docker-compose.yml.example and copy it to docker-compose.yml. You may want to change the location of the code to serve in the app, for example:

```
volumes:
  - ../appcode:/app
```

Run:

```
docker-compose up
```

Run unit tests:

```
http://IP_OF_CONTAINER:3000/tests
```

Check db connection:

```
http://IP_OF_CONTAINER:3000/testdb
```
