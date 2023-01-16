# Helidon nima - basic

```sh
mvn package
java --enable-preview -jar target/helidon-nima-examples-basic.jar
```

```sh
mvn package -Pnative-image

./target/helidon-nima-examples-basic
curl http://localhost:8080/
```