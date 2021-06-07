
<p id="Primeiro paragrafo"></p>

<!-- Nome do Projeto -->
<h1 align="center">API em NodeJS</h1>

<!-- Descrição do Projeto -->
<p align = "center"> API densenvolvida na Semana NLW5 da Rocketseat </p>

<h4 align="center"> 
	 API em NodeJS 🚀 
</h4>

## Tecnologias utilizadas

##### [Node](https://nodejs.org/)
`yarn init -y`

##### [Express](https://expressjs.com/)
`yarn add express`
`yarn add @types/express -D`

##### [Typescript](https://www.typescriptlang.org/)
`yarn add typescript -D`
`yarn add ts-node-dev -D`

##### [Sqlite3](https://www.sqlite.org/index.html)
`yarn add sqlite3`

##### [TypeORM](https://typeorm.io/)
`yarn add typeorm`
`yarn add typeorm reflect-metadata`

##### [Uuid](https://github.com/uuidjs/uuid)
`yarn add uuid @types/uuid -D`

###### Comandos mais comuns
`yarn typeorm migration:create -n <MigrationName>`
`yarn typeorm migration:run`
`yarn typeorm migration:revert`

## WebSocket

##### [Socket.io](https://socket.io/)
`yarn add socket.io @types/socket.io -D`
`yarn add socket.io-client`

### Pré-requisitos

- Ferramentas necessárias para a execução do projeto:
[Node.js](https://nodejs.org/en/) + [NPM](https://www.npmjs.com/get-npm), [Yarn](https://yarnpkg.com/), [VSCode](https://code.visualstudio.com/) e configurações.
- Além disso, é interessante contar com uma ferramenta para testar as suas rotas. O [Insomnia](https://insomnia.rest/) é uma das ferramentas mais utilizadas nesse sentido. 
- Utilize o [git](https://git-scm.com) para cuidar das versões do seu código.
- Bônus¹: No seu navegador Google Chrome instale a Json Viewer e nas opções dela altere o tema para "Dracula". 
- Bônus²: Caso ainda esteja com dúvidas em como configurar o ambiente e necessite de uma passo a passo bem detalhado pode conferir [aqui](https://www.notion.so/Configura-es-do-ambiente-Node-js-ae9fea3f78894139af4268d198294e2a)

### 🎲 Rodando o Back End (servidor)

```bash
# Clone este repositório
$ git clone <https://github.com/marcoscmartins/nlw4-node.git>

# Acesse a pasta do projeto no terminal/VSCode
$ cd api

# Instale as dependências
$ npm i

# Execute a aplicação em modo de desenvolvimento
$ yarn dev

# O servidor inciará na porta:3333 - Acesse <http://localhost:3333> no seu navegador
```
