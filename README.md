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
