# 🧪 Teste Técnico — CRUD de Usuários (React + Node/Nest)

## 📌 Objetivo

Desenvolver uma aplicação simples com:

- **Frontend:** React  
- **Backend:** Node.js (Express) ou NestJS  

A aplicação deve permitir:

- Listar usuários
- Criar usuários
- Editar usuários

---

# 🖥 Backend (API)

## 🔹 Tecnologias

- Node.js
- Express **ou** NestJS
- Banco de dados livre (pode ser em memória)

## 🔹 Modelo de Usuário

O usuário deve conter os seguintes campos:

```ts
{
  id: string | number,
  name: string,
  email: string,
  role?: string,
  createdAt: Date
}


Regras:

name é obrigatório

email é obrigatório

email deve ter formato válido

email não pode ser duplicado

id e createdAt devem ser gerados pelo backend

Retornar status HTTP apropriados (200, 201, 400, 404, etc.)

🔹 Endpoints obrigatórios
📍 Listar usuários
GET /users

📍 Criar usuário
POST /users

📍 Editar usuário
PUT /users/:id

🌐 Frontend (React)
🔹 Funcionalidades
1️⃣ Listagem de Usuários

Exibir: name, email, role

Botão "Novo Usuário"

Botão "Editar" em cada usuário

2️⃣ Criar Usuário

Formulário com:

name

email

role

Validação básica no frontend

Após salvar, retornar para listagem atualizada

3️⃣ Editar Usuário

Carregar dados do usuário selecionado

Permitir editar:

name

email

role

Após salvar, atualizar a listagem

📦 Estrutura Esperada do Projeto
/backend
/frontend
README.md

🚀 Entrega

O candidato deve entregar:

Repositório no GitHub

Código funcional

README dentro do projeto explicando:

Como rodar o backend

Como rodar o frontend

Dependências necessárias
