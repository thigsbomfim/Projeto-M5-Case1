# Projeto-M5-Case1

# Projeto individual Módulo 5



# [ API ] Academia
### 📑 Descrição
Desenvolvimento da <em>**API REST**</em> no **padrão MVC** que retorna informações das entidades de uma academia e efetua todas as operações **CRUD**: ``Clientes``, ``Produtos``, ``Atividades``, ``Franquias``.




**[ Tecnologias ]**

<samp>
  
- <em>Node.js</em> | <em>MySQL</em> | <em>Express</em> | <em>Postman</em> | <em>CORS</em> | <em>npm</em> | <em>Nodemon</em>
  
</samp>

<details>
<summary>  
  <strong>Estrutura do Diretório</strong>
</summary>
<br>

```
src/
├─ controllers/
│  ├─ clientesControl.js
│  ├─ produtosControl.js
│  ├─ atividadeControl.js
│  └─ franquiasControl.js
├─ models/
│  ├─ Clientes.js
│  ├─ Produtos.js
│  ├─ Atividade.js
│  └─ Franquias.js
├─ database/
│  ├─ db.sql
│  └─ database.js
├─ routes/
│  ├─ clientes.js
│  ├─ produtos.js
│  ├─ atividades.js
│  └─ franquias.js
└─ main.js
```

</details>


### 🎲 Iniciando o Projeto


<samp>
  
> **Warning** 
> Pré-Requisitos: Git, Node.js e um editor de código.

</samp>

```bash
# Clone o repositório
$ git clone https://github.com/thigsbomfim/Projeto-M5-Case1

# Acesse a pasta do projeto no terminal/cmd
$ cd academia

# Instale as dependências
$ npm install

# Execute a aplicação 
$ npm start

# Acesse o servidor
$ <http://localhost:3500>
```

## Rotas CRUD

### [ 1 ] <em>Franquias</em>

| Método | Rota | Descrição |
| ------ | ----- | ----------- |
| **`GET`** | **/franquias** | Retorna todas as franquias. |
|  **`GET`** | **/franquia/:id** | Retorna uma franquia. |
|  **`POST`** | **/franquia** | Cria uma nova franquia.  |
|  **`PUT`** | **/franquia/:id** | Altera os dados da franquia.
|  **`DELETE`** | **/franquia/:id** | Remove a franquia.
  
### [ 2 ] <em>Clientes</em>

| Método | Rota | Descrição |
| ------ | ----- | ----------- |
|  **`GET`** | **/clientes** | Retorna todos os clientes. |
|  **`GET`** | **/cliente/:id** | Retorna um cliente. |
|  **`POST`** | **/cliente** | Cria um novo cliente.  |
|  **`PUT`** | **/cliente/:id** | Altera os dados do cliente.
|  **`DELETE`** | **/cliente/:id** | Remove o cliente.
  
  
### [ 3 ] <em>Produtos</em>

| Método | Rota | Descrição |
| ------ | ----- | ----------- |
|  **`GET`** | **/produtos** | Retorna todos os produtos. |
|  **`GET`** | **/produto/:id** | Retorna um produto. |
|  **`POST`** | **/produto** | Cria um novo produto.  |
|  **`PUT`** | **/produto/:id** | Altera os dados do produto.
|  **`DELETE`** | **/produto/:id** | Remove o produto.


### [ 4 ] <em>Atividades</em>

| Método | Rota | Descrição |
| ------ | ----- | ----------- |
|  **`GET`** | **/atividades** | Retorna todas as atividades. |
|  **`GET`** | **/atividade/:id** |  Retorna uma atividade. |
|  **`POST`** | **/atividade** | Cria uma nova atividade.  |
|  **`PUT`** | **/atividade/:id** | Altera os dados da atividade.
|  **`DELETE`** | **/atividade/:id** | Remove a atividade.
  

