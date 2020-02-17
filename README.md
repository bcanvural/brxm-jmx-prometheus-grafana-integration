Build brxm image

```bash
mvn clean install && mvn -Pdocker.build
```

Start up docker-compose

```bash
cd docker-compose
docker-compose up -d
```

Go to grafana at http://localhost:3000 and set up a "proemetheus" data source at: http://prometheus:9090

