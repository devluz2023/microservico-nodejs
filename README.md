# projeto-node-js

1. to connect to mongodb
`docker exec -it mongo mongosh -u dev -p dev`
`use websocket`
`db.createUser({   user: "dev",   pwd: "dev",  roles: [{ role: "readWrite", db: "websocket" }]})`


```
├── README.md
├── authenticador
│   ├── api
│   │   ├── config
│   │   │   └── config.json
│   │   ├── controllers
│   │   │   └── produtoController.js
│   │   ├── index.js
│   │   ├── migrations
│   │   │   └── 20221222234111-create-produtos.js
│   │   ├── models
│   │   │   ├── index.js
│   │   │   └── produtos.js
│   │   ├── routes
│   │   │   ├── index.js
│   │   │   └── produtoRoute.js
│   │   └── services
│   │       └── produtoService.js
│   ├── package-lock.json
│   └── package.json
├── chat
│   ├── README.md
│   ├── app.js
│   ├── app.log
│   ├── clusters.js
│   ├── config.json
│   ├── controllers
│   │   ├── chat.js
│   │   ├── contatos.js
│   │   └── home.js
│   ├── error.log
│   ├── libs
│   │   └── db_connect.js
│   ├── middlewares
│   │   ├── autenticador.js
│   │   └── error.js
│   ├── models
│   │   └── usuario.js
│   ├── package.json
│   ├── public
│   │   ├── images
│   │   │   ├── glyphicons-halflings-white.png
│   │   │   └── glyphicons-halflings.png
│   │   ├── javascripts
│   │   │   └── zepto.min.js
│   │   └── stylesheets
│   │       └── style.css
│   ├── routes
│   │   ├── chat.js
│   │   ├── contatos.js
│   │   └── home.js
│   ├── server.js
│   ├── sockets
│   │   └── chat.js
│   ├── test
│   │   ├── chat.js
│   │   ├── contatos.js
│   │   ├── home.js
│   │   └── mocha.opts
│   └── views
│       ├── chat
│       │   ├── chat_script.ejs
│       │   └── index.ejs
│       ├── contatos
│       │   ├── edit.ejs
│       │   ├── index.ejs
│       │   ├── notify_script.ejs
│       │   └── show.ejs
│       ├── exit.ejs
│       ├── footer.ejs
│       ├── header.ejs
│       ├── home
│       │   └── index.ejs
│       ├── not-found.ejs
│       └── server-error.ejs
├── docker-compose.yml
├── materiais
│   ├── Gruntfile.js
│   ├── ProdutosWeb.js
│   ├── app
│   │   ├── controller
│   │   │   ├── game.js
│   │   │   ├── home.js
│   │   │   ├── pedido.js
│   │   │   ├── produtos.js
│   │   │   └── promocoes.js
│   │   ├── infra
│   │   │   ├── ProdutosDAO.js
│   │   │   └── connectionFactory.js
│   │   ├── models
│   │   │   └── pedido.js
│   │   ├── public
│   │   │   ├── css
│   │   │   │   ├── estilo_produtos.css
│   │   │   │   ├── estilo_produtos.less
│   │   │   │   └── reset.css
│   │   │   └── js
│   │   │       ├── app.js
│   │   │       ├── game.js
│   │   │       ├── javascript_project.js
│   │   │       ├── jquery_project.js
│   │   │       └── menu.js
│   │   ├── routes
│   │   │   ├── game.js
│   │   │   ├── home.js
│   │   │   ├── pedido.js
│   │   │   ├── produtos.js
│   │   │   └── promocoes.js
│   │   └── views
│   │       ├── erros
│   │       │   ├── 404.ejs
│   │       │   └── 500.ejs
│   │       ├── game
│   │       │   └── index.ejs
│   │       ├── home
│   │       │   └── index.ejs
│   │       ├── includes
│   │       │   ├── menu.ejs
│   │       │   └── rodape.ejs
│   │       ├── produtos
│   │       │   ├── form.ejs
│   │       │   └── lista.ejs
│   │       └── promocoes
│   │           └── form.ejs
│   ├── app.js
│   ├── cliente.js
│   ├── clienteAndroid.js
│   ├── comandos_uteis
│   │   ├── desricao.txt
│   │   ├── dos.txt
│   │   ├── git.txt
│   │   ├── linux.txt
│   │   ├── npm.txt
│   │   └── redes.txt
│   ├── config
│   │   ├── express.js
│   │   └── mongoConnect.js
│   ├── package.json
│   └── test
│       └── produtos.js
└── websocket
    ├── Dockerfile
    ├── package-lock.json
    ├── package.json
    ├── public
    │   ├── documento.html
    │   ├── documento.js
    │   ├── index.html
    │   ├── index.js
    │   ├── socket-front-documento.js
    │   └── socket-front-index.js
    └── src
        ├── dbConnect.js
        ├── documentosDb.js
        ├── servidor.js
        └── socket-back.js
```