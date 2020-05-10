# User Management System, Spring Boot, Vue JS, MySQL

The application structure is as follows.
- **server-side** - Service implemented using Spring boot. [More info](spring-boot-rest/README.md)
- **client-side** - A NodeJs application implemented using Vue JS. This consumes services hosted by server side.  [More info](vue-rest/README.md)

#### 1) Build Server Side

```
$ cd spring-boot-rest
$ gradlew bootJar
$ gradlew bootRun
```

#### 2) Build and run client side

```
$ cd vue-rest
$ npm run serve --port 4000
```

### Access server side using following URL

```
http://localhost:8080
```

### Access application using following URL

```
http://localhost:4000
```