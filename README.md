# projeto-node-js

1. to connect to mongodb
`docker exec -it mongo mongosh -u dev -p dev`
`use websocket`
`db.createUser({   user: "dev",   pwd: "dev",  roles: [{ role: "readWrite", db: "websocket" }]})`