<p align="center">
  <img src="./gympass.jpeg" alt="GymPass Logo e Banner" width="100%" />
</p>

# 🏋️‍♂️ GymPass

Buscador de academias conveniadas para usuários realizarem check-in nas academias mais próximas de sua localização.  
Ideal para quem quer praticidade, mobilidade e bem-estar sem complicações.

---

## 🚀 Tecnologias Utilizadas

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Fastify](https://img.shields.io/badge/Fastify-000000?style=flat&logo=fastify&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-3F51B5?style=flat)
![Dotenv](https://img.shields.io/badge/Dotenv-ECD53F?style=flat)

---

## 🛢️ Banco de Dados

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)


---

## 📍 Funcionalidades

- 🔍 Buscar academias por localização
- ✅ Check-in em academias conveniadas
- 📅 Histórico de check-ins
- 📌 Validação de distância (limite de metros)
- 🔐 Autenticação de usuários

---

## ⚙️ Como rodar o projeto

```bash
# Clone o repositório
git clone https://github.com/seuusuario/gympass.git

# Instale as dependências
npm install

# Configure as variáveis de ambiente
cp .env.example .env

# Rode as migrations do banco
npx prisma migrate dev

# Inicie o servidor
npm run dev
