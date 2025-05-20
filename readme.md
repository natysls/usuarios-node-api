# Usuários API com Node.js, Express e Prisma (MongoDB)

API simples para gerenciamento de usuários usando Node.js, Express e Prisma ORM conectado ao MongoDB.

---

## Tecnologias usadas

- **Node.js** – Ambiente onde o backend roda.
- **Express** – Framework leve pra criar rotas e lidar com requisições.
- **Prisma ORM** – Facilita o acesso e manipulação do banco de dados.
- **MongoDB** – Banco de dados NoSQL usado no projeto.
- **Thunder Client (VSCode)** – Extensão do VSCode pra testar as rotas da API de


---

## Requisitos

- Node.js instalado 
- MongoDB rodando 
- npm ou yarn instalado

---

## Funcionalidades

- Create, read, update, and delete users
- JSON-based API
- Built with Node.js and Express

---

## Getting Started

### Instalação

```bash
git clone https://github.com/yourusername/usuarios-api.git
cd usuarios-api
npm install
npx prisma init
npx prisma db push
npx prisma generate
```

### Rodando a aplicação em CMDs diferentes

```bash
node --watch server.js
npx prisma studio  
```

A API estará disponível em `http://localhost:3000`, e pode ser testada facilmente utilizando o Thunder Client, um plugin do Visual Studio Code. No entanto, essa API será consumida pela aplicação frontend ReactJS disponível em [natysls/cadastro-usuarios-web](https://github.com/natysls/cadastro-usuarios-web).

---

## 📬 API Endpoints

| Method | Endpoint       | Description           |
|--------|----------------|-----------------------|
| GET    | /users         | Lista todos os users  |
| GET    | /users/:id     | Busca um user pelo Id |
| POST   | /users         | Cria novo user        |
| PUT    | /users/:id     | Atualiza um user      |
| DELETE | /users/:id     | Deleta um user        |

---

## 📺 Fonte da Aula
Este projeto foi baseado na seguinte aula do Youtube:
[Criando uma API do ZERO com Node.js e Banco de Dados](https://youtu.be/PyrMT0GA3sE?si=TFYwPy-aiu8kAaR8)
