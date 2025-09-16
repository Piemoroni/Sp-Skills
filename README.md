# Projeto Backend Node.js

Este repositório contém instruções para iniciar um projeto backend em Node.js.

## Passo a passo

### 1-) Inicializar o projeto

-npm init -y

### 2-) Instalar dependências essenciais

-npm install 

### 3-) Pastas recomendada

/src

/controllers

/routes

/models

server.js

### 4-) Criar arquivo principal

Crie `server.js` dentro da pasta raiz:


const express = require("express"); 
const cors = require("cors");

const app = express();

app.use(express.json()); 
app.use(cors()); 

app.use(---);
app.use(---);
app.use(---);

app.listen(3000, () => {
    console.log("Servidor online na porta 3000");
});


### 5-) Rodar o servidor

node server.js

O servidor deve estar disponível em `http://localhost:3000`.


### 6-) Próximos passos

* Criar rotas adicionais.

* Configurar banco de dados.

* Implementar controllers e routes.



## 7-) Salvar, commitar e enviar alterações
