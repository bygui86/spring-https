
# Spring Boot HTTPS

## Run

`WARN: the password for the keystore must be the same as in the application.properties (e.g.: secret)`

```shell
keytool -genkeypair -alias test -keyalg RSA -keysize 2048 -storetype PKCS12 -keystore src/main/resources/keystore/test.p12 -validity 3650

mvnw clean spring-boot:run
```

---

## Links
* https://www.baeldung.com/spring-boot-https-self-signed-certificate
