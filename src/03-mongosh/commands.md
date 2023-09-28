## Connect to container
```sh
docker-compose exec mongodb sh
```

## Connect with mongosh

```sh
mongosh "mongodb+srv://iegomezc:QFMVpM8t9imeoO4x@cluster0.uaztcro.mongodb.net/"
mongosh "mongodb://root:root12345@localhost:27017/?authMechanism=DEFAULT&tls=false"
```

```sh
show dbs
show collections
```

```sh
use("PlatziStore")
db.Productos.find({price:500})
```

