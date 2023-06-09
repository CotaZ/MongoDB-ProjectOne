## Connect to container

```sh
docker-compose exec mongodb bash
```

## Connect with mongosh Atlas or Docker

```sh
mongosh "mongodb://luis:alvarez@localhost:27017/?authMechanism=DEFAULT"
mongosh "mongodb+srv://admin:admin123@admin.gclcmzh.mongodb.net/"
```

```sh
show dbs
show collections
```

```sh
use ("platzi_store")
db.products.find()    
```