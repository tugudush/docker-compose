Setup the following env files.

env/mongo.env
```
MONGO_INITDB_ROOT_USERNAME=yourmongodbusername
MONGO_INITDB_ROOT_PASSWORD=yourmongodbpassword
```

env/backend.env
```
MONGODB_USERNAME=yourmongodbusername
MONGODB_PASSWORD=yourmongodbpassword
```

build and run (-d for detach)
```
docker compose up -d
```

stop and remove containers (-v to include volumes)
```
docker compose down -v
```