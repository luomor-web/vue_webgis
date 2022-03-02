```shell
sudo docker-compose build
sudo docker-compose down
sudo docker-compose up
sudo docker-compose up -d

sudo docker-compose up gis-mongodb
sudo docker-compose up -d gis-mongodb
sudo docker-compose stop gis-mongodb
sudo docker-compose rm gis-mongodb

sudo docker-compose up gis-mongo-express
sudo docker-compose up -d gis-mongo-express
sudo docker-compose stop gis-mongo-express
sudo docker-compose rm gis-mongo-express
```

```shell
sudo docker network create --subnet=172.19.0.0/16 gis-network
```