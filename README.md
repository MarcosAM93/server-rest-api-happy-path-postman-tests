# Server Rest API - Postman Tests

Testes de happy path do SERVER REST API, utilizando Postman e Newman.

## Pré-requisitos

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en/) (v20.18.0)
- npm (v10.8.2)
- [Postman](https://www.postman.com/downloads/)
- [Newman](https://www.npmjs.com/package/newman)

> É recomendado utilizar Node.js `v20.18.0` e npm `v10.8.2` ou superiores.

## Instalação

```bash
git clone https://github.com/MarcosAM93/postman-server-rest-api.git
cd postman-server-rest-api
npm install -g newman

newman run "server rest api happy path/server rest api happy path.postman_collection.json" \ -e "server rest api happy path/server rest api happy path.postman_environment.json"
```
