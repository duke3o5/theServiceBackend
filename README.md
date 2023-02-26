# theServiceBackend

1). npm init -y
2). create server.js and paste =>{`const jsonServer = require('json-server')
const server = jsonServer.create()
const router = jsonServer.router('db.json')
const middlewares = jsonServer.defaults()

server.use(middlewares)
server.use(router)
server.listen(3000, () => {
  console.log('JSON Server is running')
})`}

3). npm i json-server cors
4). npm i json-serve
5). create db.json and paste your data