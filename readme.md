## init
```bash

gradle init --type java-application
```

## build

```bash
gradle clean shadowJar
```


## run

```bash
java -jar build/libs/producer-all.jar
```

https://docs.confluent.io/platform/current/installation/installing_cp/zip-tar.html#prod-kafka-cli-install

## check schemas
http://<ip>:8082/schemas



## Reference
[confluent schema registry configure and install](https://docs.confluent.io/platform/current/installation/installing_cp/zip-tar.html#prod-kafka-cli-install)

[schema registry apis](https://docs.confluent.io/platform/current/schema-registry/develop/api.html)



