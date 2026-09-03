# 📚 API de Livros

<p align="center">
  <strong>API REST para gerenciamento de livros</strong>
</p>

---

## 👩‍💻 Desenvolvedora

**Mayara De Oliveira Sant’Anna**

🎓 **Curso:** Técnico em Informática para Internet
🏫 **Instituição:** ETEC
👥 **Turma:** 3C
👨‍🏫 **Professor:** Anderson Vanin
📅 **Ano:** 2026

---

## 📖 Sobre o projeto

A **API de Livros** é um projeto acadêmico desenvolvido com o objetivo de colocar em prática conceitos de **desenvolvimento de APIs, programação back-end e banco de dados**.

A aplicação será responsável pelo gerenciamento de livros, permitindo realizar operações como cadastro, consulta, atualização e exclusão de registros.

O projeto está sendo desenvolvido de forma gradual, acompanhando as etapas apresentadas em aula.

---

## 🎯 Objetivos

* 🚀 Desenvolver uma API REST utilizando Python;
* ⚡ Aprender a utilizar o framework FastAPI;
* 🗄️ Integrar a aplicação a um banco de dados MySQL;
* 🔄 Implementar operações CRUD;
* ✅ Trabalhar com validação e organização de dados;
* 🌐 Desenvolver posteriormente uma interface web para consumir a API;
* 💻 Praticar organização e versionamento de projetos utilizando Git e GitHub.

---

## 🛠️ Tecnologias

| Tecnologia                    | Utilização                           |
| ----------------------------- | ------------------------------------ |
| 🐍 **Python**                 | Linguagem principal                  |
| ⚡ **FastAPI**                 | Desenvolvimento da API               |
| 🚀 **Uvicorn**                | Servidor da aplicação                |
| 🗃️ **SQLAlchemy**            | Comunicação com o banco de dados     |
| 🐬 **MySQL**                  | Banco de dados                       |
| 🔌 **PyMySQL**                | Conexão Python com MySQL             |
| 📋 **Pydantic Settings**      | Configuração e variáveis de ambiente |
| 🌐 **HTML, CSS e JavaScript** | Interface web futura                 |
| 🐙 **Git & GitHub**           | Versionamento do projeto             |

---

## 📚 Funcionalidades

Ao final do desenvolvimento, a API contará com:

* ➕ **Cadastrar livros**
* 📖 **Listar livros**
* 🔎 **Consultar um livro específico**
* ✏️ **Atualizar informações**
* 🗑️ **Excluir livros**
* ❤️ **Verificar o status da API e do banco de dados**

### 📌 Dados dos livros

Cada livro poderá possuir:

* 🔢 ID
* 📕 Título
* ✍️ Autor
* 📅 Ano de publicação
* ✅ Disponibilidade

---

## 🏗️ Desenvolvimento atual

### ✅ Etapa 1 — Estrutura e conexão

Nesta primeira etapa foram realizadas as configurações iniciais do projeto:

* 📁 Organização da estrutura da aplicação;
* 🐍 Configuração do ambiente Python;
* 📦 Instalação das dependências;
* 🗄️ Criação do banco de dados MySQL;
* 🔐 Configuração das variáveis de ambiente;
* 🔗 Configuração da conexão entre FastAPI e MySQL;
* ⚡ Criação da aplicação FastAPI;
* ❤️ Implementação da rota de verificação `/health`;
* 📑 Configuração da documentação automática da API.

> 🚧 O projeto continuará sendo desenvolvido nas próximas etapas, com a implementação das operações de gerenciamento dos livros e, posteriormente, da interface web.

---

## 🔗 Rotas previstas

| Método   | Rota           | Função             |
| -------- | -------------- | ------------------ |
| `POST`   | `/livros`      | ➕ Criar livro      |
| `GET`    | `/livros`      | 📚 Listar livros   |
| `GET`    | `/livros/{id}` | 🔎 Buscar livro    |
| `PUT`    | `/livros/{id}` | ✏️ Atualizar livro |
| `DELETE` | `/livros/{id}` | 🗑️ Excluir livro  |

### ❤️ Health Check

```http
GET /health
```

Utilizada para verificar se a API está funcionando e se a conexão com o banco de dados foi estabelecida corretamente.

---

## 📂 Estrutura

```text
api-livros/
│
├── 📂 app/
│   ├── __init__.py
│   ├── database.py
│   └── main.py
│
├── 📂 database/
│   └── biblioteca_db.sql
│
├── 📄 requirements.txt
├── 📄 .gitignore
└── 📄 README.md
```

---

## 📈 Evolução do projeto

**Parte 1** ✅ Estrutura e conexão com o banco
**Parte 2** 🔄 Cadastro e consulta de livros
**Parte 3** 🔄 Atualização e exclusão de livros
**Parte 4** 🔄 Interface web

---

## 👨‍🏫 Projeto acadêmico

Projeto desenvolvido por **Mayara De Oliveira Sant’Anna** durante as aulas do curso **Técnico em Informática para Internet**, sob orientação do professor **Anderson Vanin**.

⭐ **Projeto em desenvolvimento — 2026**
