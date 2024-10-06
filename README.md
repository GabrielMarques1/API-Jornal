# API-Jornal

Esta é uma API para gerenciar notícias, permitindo criar, listar, atualizar e deletar notícias.

Tecnologias Utilizadas
Node.js
Fastify
Prisma
PostgreSQL
Instalação
Clone o repositório: https://github.com/GabrielMarques1/API-Jornal

cd news.crud.api

Configure o banco de dados no arquivo .env:

Execute as migrações do Prisma:

npx prisma migrate dev
Inicie o servidor:

npm run dev
Endpoints
GET /news: Listar todas as notícias
GET /news/:id: Obter uma notícia por ID
POST /news: Criar uma nova notícia
PUT /news/:id: Atualizar uma notícia existente
DELETE /news/:id: Deletar uma notícia por ID
