## Connect to container

```sh
docker-compose exec mongodb bash
```

## Conect with mongosh

```sh
mongosh "mongodb+srv://lash1co:lash1coadmin123@mongodb101.6owlp4a.mongodb.net/test"
mongosh "mongodb://root:root123@localhost:27017/?authMechanism=DEFAULT&tls=false"
```

```sh
show dbs
show collections
```

```sh
use("platzi_store")
db.zips.find({state:"NY"}).count()
db.products.find()
```