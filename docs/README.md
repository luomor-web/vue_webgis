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

sudo npm install -g nodemon

npm install @mapbox/node-pre-gyp

rm -rf node_modules
npm install

# node-pre-gyp install --fallback-to-build

sudo yum install gcc-c++

npm run server
npm run client

mongo mongodb://root:123456@localhost:27017/admin

db.createUser({
    user:'test',
    pwd:'123456',
    roles:[
        {
            role:'userAdminAnyDatabase',
            db:'admin'
        }
    ]
})

mongo mongodb://test:123456@localhost:27017/admin

use vue_webgis
db.createUser({
    user:'test',
    pwd:'123456',
    roles:[
    {
        role:'readWrite',
        db:'vue_webgis'
    }
    ]
})
mongo mongodb://test:123456@localhost:27017/vue_webgis

```

```shell
sudo docker network create --subnet=172.19.0.0/16 gis-network
```

```
nodemon
```