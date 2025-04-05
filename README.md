# Barber Shop API & UI - README

## 🧑‍💻 Projeto de Agendamento de Atendimento em Barbearia

Este projeto consiste em um desafio para o bootcamp da DIO Decola Tech da Avanade, com um sistema completo para agendamento de atendimentos em uma barbearia, utilizando um **backend em Java com Spring** e um **frontend em Angular**. O backend expõe uma API RESTful para gerenciamento dos agendamentos e o frontend consome essa API para criar uma interface de usuário interativa.

O projeto foi dividido em dois repositórios distintos:

- **Backend:** `barber-shop-api`
- **Frontend:** `barber-shop-ui`

## 💻 Sobre o Projeto

### 1. **barber-shop-api (Backend)**

Este projeto é um sistema backend criado com Java utilizando o framework **Spring Boot**. Ele se comunica com um banco de dados PostgreSQL para armazenar os agendamentos e usa **JPA com Hibernate** para gerenciamento dos dados.

#### Funcionalidades:

- API RESTful para agendamento de atendimentos
- Integração com banco de dados PostgreSQL usando JPA
- Migrations do banco de dados gerenciadas com **Flyway**
- Estrutura organizada e boas práticas de desenvolvimento em backend

### 2. **barber-shop-ui (Frontend)**

O frontend é desenvolvido com **Angular** e utiliza a **Angular Material** para fornecer uma interface de usuário moderna e responsiva. A aplicação consome a API REST do backend para interagir com o usuário e mostrar os agendamentos de forma eficiente.

#### Funcionalidades:

- Consumo da API REST do backend
- Tela de agendamento de atendimento
- Interface responsiva e organizada utilizando Angular Material
- Componentização para reaproveitamento de código

## 📚 Pré-requisitos

### Backend (barber-shop-api)
Antes de começar com o backend, é necessário ter conhecimentos intermediários nas seguintes tecnologias:

- **Java** | Intermediário
- **SQL** | Intermediário
- **Gradle** | Básico
- **Spring** | Básico
- **Docker** | Básico (opcional)
- **Docker Compose** | Básico (opcional)

### Frontend (barber-shop-ui)
Para o frontend, é necessário ter conhecimentos intermediários nas seguintes tecnologias:

- **Javascript** | Intermediário
- **Typescript** | Intermediário
- **HTML** | Intermediário
- **CSS** | Intermediário
- **Docker** | Básico (opcional)
- **Docker Compose** | Básico (opcional)

## 🛠️ Habilidades e Sub-habilidades

### Backend (barber-shop-api)
Neste conteúdo, os alunos irão aprender as seguintes habilidades:

- Trabalhar com **verbos HTTP** de forma correta
- Comunicação com **backend** utilizando Spring
- Gerenciar **versionamento de banco de dados** com Flyway
- Gerenciar comunicação com o banco de dados usando **JPA com Hibernate**

### Frontend (barber-shop-ui)
As habilidades a serem desenvolvidas incluem:

- Criar e consumir uma **API REST** no frontend com Angular
- **Componentização** de UI para reaproveitamento de código e organização do projeto
- Desenvolvimento de interfaces responsivas com **Angular Material**

## 🎯 Objetivos e Resultados Esperados

Após a conclusão deste projeto, os alunos estarão aptos a:

### Backend
- Criar um projeto **Java com Spring** para APIs RESTful
- Construir um backend robusto para agendamento de atendimentos em uma barbearia
- Integrar o backend com **PostgreSQL** e gerenciar migrations com **Flyway**

### Frontend
- Criar uma **aplicação Angular** para consumir uma API REST
- Desenvolver interfaces de usuário responsivas e modernas utilizando **Angular Material**
- Organizar o código frontend em componentes reutilizáveis

## 🚀 Como Rodar o Projeto

### 1. Backend (barber-shop-api)

#### Pré-requisitos:
- JDK 11 ou superior
- Docker (opcional, caso queira rodar o PostgreSQL em contêiner)
- Gradle (opcional, mas recomendado para gerenciamento de builds)

#### Instruções:

1. Clone o repositório do backend:
    ```bash
    git clone https://github.com/Eucimarf/desafio-barber-shop.git
    cd barber-shop-api
    ```

2. Configure o banco de dados **PostgreSQL** (via Docker ou localmente).

3. Se estiver utilizando Docker, execute:
    ```bash
    docker-compose up -d
    ```

4. Abra o projeto no seu editor preferido e execute o backend:
    ```bash
    ./gradlew bootRun
    ```

A API estará disponível em `http://localhost:8080`.

### 2. Frontend (barber-shop-ui)

#### Pré-requisitos:
- Node.js
- Angular CLI

#### Instruções:

1. Clone o repositório do frontend:
    ```bash
    git clone https://github.com/Eucimarf/desafio-barber-shop.git
    cd barber-shop-ui
    ```

2. Instale as dependências:
    ```bash
    npm install
    ```

3. Execute a aplicação frontend:
    ```bash
    ng serve
    ```

A aplicação estará disponível em `http://localhost:4200`.

## 🤝 Contribuições

Este projeto foi desenvolvido como parte de um curso de desenvolvimento backend e frontend. Contribuições são bem-vindas! Para contribuir, siga os seguintes passos:

1. Faça um fork deste repositório.
2. Crie uma nova branch (`git checkout -b feature/nova-feature`).
3. Commit suas mudanças (`git commit -am 'Adiciona nova feature'`).
4. Envie para o repositório remoto (`git push origin feature/nova-feature`).
5. Abra um pull request.


---

**Desenvolvedor:**
<!--  -->
<table align="center">
<thead>
  <tr>
    <td>
        <p align="center">Expert</p>
        <a href="https://github.com/juniorjrjl">
        <img src="https://avatars.githubusercontent.com/u/6619093?u=0afe982a654793dfc9e886acab8b417aa632f511&v=4" alt="@felipeAguiarCode"><br>
      </a>
    </td>
    <td colspan="3">
    <p>🎉 10y+ em desenvolvimento Backend (Principalmente com Java mas já atuei com Scala, Python, Kotlin).
      <br/>
     🌟 Desenvolvedor backend - CAJU
      <br/>
    👨‍💻 Foco em back-ends
    </p>
      <a 
      href="https://www.linkedin.com/in/josé-luiz-abreu-cardoso-junior-18483872/" 
      align="center">
           <img 
            align="center" 
            alt="Material de Apoio" 
            src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"
            >
        </a>
        <a href="https://www.instagram.com/junior.jose.lz/" target="_blank">
            <img 
              align="center" 
              alt="Instagram" 
              src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"
            >
        </a>
    </td>
  </tr>
</thead>
</table>
<!--  -->

<br/>
<br/>

**Ano:** 2025  
**Tecnologias Usadas:** Java, Spring, Angular, PostgreSQL, Flyway, Docker