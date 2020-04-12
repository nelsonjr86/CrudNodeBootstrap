# CrudNodeMongoBootstrap

# Tutorial: Desenvolvendo uma Aplicação RESTful API em Node.Js & Express.Js com MongoDb

Código desenvolvido do tutorial do CRUD em Node.Js, Express e MongoDb.

- Incluir, Editar e Deletar registros do MongoDB
- Criar filtro e paginação utilizando javaScript

## Recursos utilizados no desenvolvimento:

- Node.Js; https://linuxize.com/post/how-to-install-node-js-on-ubuntu-18.04/
- Express.Js ~ 4.17.1; https://www.npmjs.com/package/express
- MongoDb; https://docs.mongodb.com/manual/tutorial/install-mongodb-on-ubuntu/
- Mongoose ~5.9.7; https://www.npmjs.com/package/mongoose
- body-parser; https://www.npmjs.com/package/body-parser
- JSON data (para retornar os dados);

# Também foi instalado Robo 3T
https://www.techrunnr.com/install-robomongo-robo-3t-on-ubuntu-18-04/


## Executar Localmente

Caso você deseja executar o projeto na sua máquina local, basta seguir os passos abaixo:

## Começando...

Para começar, você deve simplesmente clonar o repositório do projeto na sua máquina e instalar as dependências.

### Pre-Requisitos

Antes de instalar as dependências no projeto, você precisa já ter instalado na sua máquina:

* **Node.Js**: Caso não tenha, basta realizar o download [Aqui](https://nodejs.org/en/)
* **MongoDb**: Caso também não tenha, basta realizar o download [Aqui](https://www.mongodb.com/download-center#community)

p.s.: o MongoDb caso você decida conectar a sua base de dados de maneira local. Caso não, basta usar 
a base de dados do MongoDb em Cloud:

### Executando a Aplicação

Bom, agora na mesma tela do cmd, basta iniciar o server para o projeto ser executado localmente.

```
node server.js
```

Depois, você precisará abrir um outro terminal na sua máquina e iniciar o MongoDb. Basta digitar na tela do cmd o seguinte comando:

```
mongod
```

Caso o MongoDb esteja devidamente instalado em sua máquina, ele iniciará o serviço mostrando que a port 27017 foi iniciada.


Agora, abre a página da aplicação em `http://localhost:3000`. E pronto a aplicação será executada de maneira local na sua máquina.        


p.s.: no projeto, disponibilizei 2 maneiras de realizar a conexão de dados com o MongoDb através do Mongoose:

* **De maneira local**: utilizando o MongoDb;
* **De maneira em cloud**: utilizando o Modulus;



# …or create a new repository on the command line
# echo "# CrudNodeBootstrap" >> README.md
# git init
# git add README.md
# git commit -m "first commit"
# git remote add origin https://github.com/nelsonjr86/CrudNodeBootstrap.git
# git push -u origin master
                
# …or push an existing repository from the command line
# git remote add origin https://github.com/nelsonjr86/CrudNodeBootstrap.git
# git push -u origin master
