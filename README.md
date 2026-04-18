# 🛒 StorePanel — Painel Administrativo de E-commerce

Dashboard administrativo completo para gestão de produtos, desenvolvido com foco em organização de dados, experiência do usuário e simulação de um sistema real de operação comercial.

---

## 🚀 Tecnologias utilizadas

* **Frontend:** Vue.js + Vite
* **Backend:** Node.js + Express
* **Banco de Dados:** PostgreSQL
* **Comunicação:** Axios

---

## ⚙️ Funcionalidades

✔ Cadastro de produtos
✔ Edição de produtos
✔ Exclusão de produtos
✔ Listagem em tempo real
✔ Busca dinâmica
✔ Feedback visual (mensagens)
✔ Loading em ações
✔ Dashboard com total de produtos

---

## 🖥️ Interface

Sistema com layout moderno contendo:

* Sidebar de navegação
* Cards de métricas
* Formulário dinâmico
* Tabela estilizada com ações

---

## 📦 Estrutura do projeto

```
painelecommerce/
├── backend/
│   ├── server.js
│   └── db.js
│
├── frontend/
│   ├── src/
│   │   └── App.vue
│   └── package.json
```

---

## ▶️ Como rodar o projeto

### 🔹 Backend

```bash
cd backend
npm install
node server.js
```

---

### 🔹 Frontend

```bash
cd frontend
npm install
npm run dev
```

---

## 🌐 Endpoints da API

* `GET /products` → listar produtos
* `POST /products` → criar produto
* `PUT /products/:id` → atualizar produto
* `DELETE /products/:id` → deletar produto

---

## 🎯 Objetivo do projeto

Este projeto foi desenvolvido com o objetivo de:

* Praticar integração entre frontend e backend
* Trabalhar com banco de dados relacional
* Simular um sistema administrativo real
* Evoluir habilidades em desenvolvimento fullstack

---

## 📌 Melhorias futuras

* 📊 Gráficos no dashboard
* 🔐 Sistema de autenticação (login)
* 📱 Responsividade (mobile)
* 🎨 UI/UX mais avançado

---

## 👨‍💻 Autor

Desenvolvido por **João Pedro Silva**
