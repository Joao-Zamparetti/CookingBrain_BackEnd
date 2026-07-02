<img width="1920" height="899" alt="image" src="https://github.com/user-attachments/assets/e48ec491-8a4e-458d-9dd1-33f62ff97c93" />


# 🍽️ CookingBrain - Back-end

<p align="center">
  API REST desenvolvida em <strong>Java + Spring Boot</strong> para o sistema <strong>CookingBrain</strong>, um ERP voltado para a gestão inteligente de restaurantes.
</p>

---

## 📖 Sobre o Projeto

O **CookingBrain** é um sistema ERP criado para otimizar a administração de restaurantes, automatizando processos como controle de estoque, gerenciamento de produtos, pedidos, clientes, fornecedores e análise financeira.

Este repositório contém o **Back-end**, responsável por toda a lógica de negócio da aplicação, autenticação de usuários, persistência dos dados e disponibilização de uma API REST para comunicação com o Front-end.

---

## Principais Funcionalidades

-  Autenticação de usuários
-  Controle de usuários e permissões
-  Gerenciamento de estoque
-  Cadastro de produtos
-  Gerenciamento de pedidos
-  Dashboard com indicadores
-  Relatórios gerenciais
-  Cálculo de markup e margem de lucro
-  Estatísticas de vendas
-  API REST documentada

---

# 🛠 Tecnologias Utilizadas

### Linguagem

- Java

### Framework

- Spring Boot

### Módulos Spring

- Spring Web
- Spring Data JPA
- Spring Security
- Spring Validation (Bean Validation)
- Spring OAuth2

### Documentação

- Springdoc OpenAPI (Swagger)

### Persistência

- Hibernate
- PostgreSQL (Supabase)

### Build

- Maven

### Bibliotecas

- Lombok
- Jakarta Validation
- OAuth2
- OpenAPI / Swagger UI

### Infraestrutura

- Render (Hospedagem da API)
- Supabase (Banco de Dados PostgreSQL)

### Controle de Versão

- Git
- GitHub

---

# 🏛 Arquitetura

A aplicação foi desenvolvida seguindo uma arquitetura em camadas para facilitar manutenção, organização e escalabilidade.

```
Controller
      │
      ▼
Service
      │
      ▼
Repository
      │
      ▼
Banco de Dados
```

Principais pacotes:

```
src
├── controller
├── service
├── repository
├── model
├── dto
├── config
├── security
├── validation
├── exception
└── util
```

---

# 🔒 Segurança

O sistema implementa diversos mecanismos para garantir a proteção das informações.

Entre eles:

- Autenticação via OAuth2;
- Spring Security;
- Controle de acesso por perfis;
- Criptografia de senhas;
- Validação das requisições;
- Proteção dos endpoints da API.

---

# ✔️ Validação

Para garantir a integridade dos dados recebidos pela API, o projeto utiliza **Bean Validation** através das anotações do Jakarta Validation.

Exemplos:

- `@Valid`
- `@NotNull`
- `@NotBlank`
- `@Email`
- `@Size`
- `@Positive`

---

# 📖 Documentação da API

Toda a API encontra-se documentada utilizando **Swagger (Springdoc OpenAPI)**.

Após iniciar o projeto, a documentação pode ser acessada em:

```
http://localhost:8080/swagger-ui/index.html
```

Caso a aplicação esteja publicada:

```
https://cookingbrain-backend.onrender.com
```

---

# 🗄 Banco de Dados

O CookingBrain utiliza um banco de dados **PostgreSQL** hospedado na plataforma **Supabase**.

A comunicação é realizada através do Spring Data JPA juntamente com o Hibernate, proporcionando maior produtividade e segurança na manipulação dos dados.

---

# ☁️ Infraestrutura

| Serviço | Plataforma |
|----------|------------|
| API REST | Render |
| Banco de Dados | Supabase PostgreSQL |
| Documentação | Swagger/OpenAPI |
| Controle de Versão | GitHub |

---

# 🔗 Integração

A API é consumida pelo Front-end desenvolvido em **Vue.js**, hospedado na plataforma **Vercel**, utilizando requisições HTTP para comunicação entre cliente e servidor.

---

# 👨‍💻 Equipe de Desenvolvimento

- Felipe
- Gustavo
- Tonetto
- Gianluca
- Vitor
- Israel

---

# 📄 Licença

Este projeto foi desenvolvido para fins acadêmicos durante o curso **Técnico em Desenvolvimento de Sistemas - SENAI**.

Seu objetivo é aplicar conceitos de desenvolvimento Full Stack, arquitetura de software, APIs REST, banco de dados e boas práticas de programação.
