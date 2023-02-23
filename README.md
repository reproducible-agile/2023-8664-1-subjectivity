# Subjectivity 



## Dependencies

```
JAVA 8+
MAVEN 3.6+
PostgreSQL 10+
POSTGIS (optional)
Node 14.0+
NPM 6.0+
```

## Building from source (client and server applications)
First, create a database using the sql files in `./database/` folder.

Then, adjust the configurations in `./annotation-server/src/main/resources/application.properties`.

```
bash ./build.prod
```
After the build process finished, the final war file can be found in: `./annotation-server/target/subjectivity.war`.



## Run locally
For running the server application locally, go to  `./annotation-server/`, and run the following command:

```
mvn spring-boot:run

```

For running the client application, follow the instruction in `./subjectivity-client/`.