
## Projeto Gobarber Backend - Bootcamp RocketSeat

#### O Projeto

O projeto GoBarber Backend é uma API que esta disponibilizada para os aplicativos web e mobile.

---
### Pré-Requisitos

 - **<span style="color:red"> *Esta aplicação requer instalação do NodeJS 8+* </sppan>**
 - **<span style="color:red"> *Esta aplicação requer instalação do NPM ou YARN* </sppan>**
 - **<span style="color:red"> *Esta aplicação requer instalação do Mongodb* </sppan>**
 - **<span style="color:red"> *Esta aplicação requer instalação do Redis* </sppan>**
 - **<span style="color:red"> *Esta aplicação requer instalação do Postgres Database* </sppan>**
 - **<span style="color:red"> *Esta aplicação requer um servidor de email e sua escolha* </sppan>**

#### Atencao

O arquivo `.env` e necessario. O arquivo `.env.example` pode ser utilizado como template.

---
### 1 - Instalação

Primeiro clone o repositório no diretório desejado:

```
$ cd <my directory>
```

Clonar o repositório:

```
$ git clone https://github.com/robsonnjunnior/GoBarber-Backend
```

Acessar o diretório do projeto:
```
$ cd GoBarber-Backend
```

Instalar as dependências:
   - npm:
```
$ npm install
```

   - yarn:
```
$ yarn install
```
---
### 2 - Start da aplicação

O banco de dados Postgres, Mongodb e o Redis precisam estar disponiveis e online para que os passos a seguir possam ser executados sem erros.

Quando finalizado a instalação, realizar o start da aplicação:

   - npm:
```
$ npm run dev
```

   - yarn:
```
$ yarn dev
```

Realizar o start da fila de mensagens de email:

   - npm:
```
$ npm run queue
```

   - yarn:
```
$ yarn queue
```

Link da api `http://localhost:3333/`

---

### Licença

MIT
