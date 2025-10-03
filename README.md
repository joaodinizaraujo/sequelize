# 📌 Projeto Node.js + Sequelize + MySQL

Este projeto é uma aplicação **CRUD de usuários** com gestão de endereços, utilizando **Sequelize** como ORM, **Express** para rotas e **Handlebars** no front-end.  

---

## ✅ Funcionalidades Implementadas
- 👤 **CRUD de Usuários**: cadastrar, listar, editar e excluir.  
- 🏠 **Gestão de Endereços**: cada usuário pode ter múltiplos endereços.  
- 🔗 **Relacionamentos Sequelize**: `User (1)` → `(N) Address`.  
- 🎨 **Interface Web** com Handlebars e CSS responsivo.  
- ✔️ **Validações de formulários** e mensagens de erro amigáveis.  
- 🛡️ **Tratamento de erros** e logs detalhados no servidor.  

---

## 🛠️ Tecnologias Utilizadas
- **Back-end**: Node.js, Express.js  
- **Banco de Dados**: MySQL + Sequelize  
- **Front-end**: Handlebars + CSS customizado  
- **Ferramentas**: Nodemon, MySQL Workbench  

---

## 🚀 Como Rodar o Projeto

### 1. Clonar o repositório
```bash
git clone <url-do-repositorio>
cd meu-projeto-sequelize
```

### 2. Instalar dependências
```bash
npm install
```

### 3. Configurar o banco de dados MySQL
```bash
CREATE DATABASE nodesequelize CHARACTER SET utf8mb4 COLLATE utf8mb4_unicode_ci;
```


### 4. Rodar o projeto
```bash
npm run dev
```
