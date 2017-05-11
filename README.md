# Scrabble Helper API #

## RUN Intellij Mode ##

Import `JettyLauncher.xml` as an IntelliJ Run Configuration

Access via `http://localhost:8080/words/docker` 

## RUN Docker Mode ##
```
docker-compose up
```

Access via `http://<YOUR_DOCKERHOST>:18080/words/docker`

## RUN SBT Mode ##

```sh
$ source /scripts/launch-postgres.sh
$ sbt
> jetty:start
```

Access via `http://localhost:8080/words/docker` 

