# 🏬 Loja de Tênis – Projeto Final (Desenvolvimento Web com .NET 6 MVC)

Este projeto é uma aplicação web completa desenvolvida em dupla como trabalho final da disciplina de Desenvolvimento Web. O objetivo é simular um sistema real de e-commerce focado em uma **loja de tênis**, com gerenciamento de produtos, pedidos, usuários, pagamentos, e relatórios administrativos.

---

## ✅ Funcionalidades

- 🧾 Cadastro e gerenciamento de produtos, com imagens e categorias.
- 📂 Cadastro de categorias e organização de catálogo.
- 🧍 Cadastro de clientes e seus respectivos pedidos.
- 📦 Controle de estoque por produto.
- 💳 Registro de pagamentos vinculados aos pedidos.
- 👨‍💼 Área administrativa para gerenciamento de usuários.
- 📊 Geração de relatórios de vendas.
- 🔐 Autenticação de usuários e proteção de rotas administrativas.

---

## 🛠️ Tecnologias Utilizadas

| Camada     | Tecnologia                                 |
|------------|---------------------------------------------|
| Frontend   | Razor Pages (.cshtml), Bootstrap 5, jQuery |
| Backend    | ASP.NET Core MVC 6 (C#)                    |
| Banco      | SQL Server Express (LocalDB) via EF Core  |
| ORM        | Entity Framework Core + Dapper (comparativo) |
| IDE        | Visual Studio 2022+                        |
| Git        | Versionamento com commits por etapas      |

---

## 📁 Estrutura de Diretórios

LojaTenis/
│
├── Controllers/ 
# Controladores MVC
├── Models/ 
# Entidades de domínio (POCO)
├── Views/ 
# Interfaces (Razor Pages)
├── Data/ 
# Contexto do EF Core
├── Services/ 
# Regras de negócio e integração
├── wwwroot/ 
# CSS, JS, Imagens
└── README.md 
# Documentação do projeto

|Desenvolvedores|
|Eduardo Marques|
|Jonatas Davi|
