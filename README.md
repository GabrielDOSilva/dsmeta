# DSMeta

Projeto desenvolvido durante meus estudos de Java e Spring Boot, baseado no projeto da Semana Spring React da DevSuperior.

O projeto consiste em uma aplicação para consulta de vendas, utilizando um backend desenvolvido com Spring Boot e uma interface frontend separada.

## 🚀 Tecnologias utilizadas

### Backend

- Java 11
- Spring Boot 2.7.1
- Spring Web
- Spring Data JPA
- Spring Security
- Hibernate
- H2 Database
- Maven
- Twilio

### Frontend

- React
- TypeScript
- HTML
- CSS

## 🏗️ Estrutura do projeto

O projeto é dividido em duas partes principais:


dsmeta
├── backend
└── frontend

Controller
    ↓
Service
    ↓
Repository
    ↓
Database

## ⚙️ Backend

O backend foi desenvolvido utilizando Spring Boot e disponibiliza uma API REST para consulta das informações de vendas.

A estrutura do backend possui:

- Controllers
- Services
- Repositories
- Entities
- Configurações de segurança

A camada Service é responsável pelo processamento das regras da aplicação antes da consulta ao banco de dados.

## 📊 Consulta de vendas

O sistema permite consultar vendas utilizando um período de datas.

A consulta possui suporte para:

- Data inicial
- Data final
- Paginação

Quando as datas não são informadas, o sistema utiliza como período padrão os últimos 365 dias até a data atual.

## 🌐 API REST

O backend disponibiliza endpoints para consulta das informações de vendas.

### Vendas

`GET /sales`

Retorna informações de vendas de acordo com o período informado e os parâmetros de paginação.

Também existe uma funcionalidade para envio de notificações relacionadas às vendas utilizando integração com o serviço Twilio.

## 🗄️ Banco de dados

O projeto utiliza o H2 Database durante a execução da aplicação.

O acesso aos dados é realizado utilizando Spring Data JPA e Hibernate.

## 🔐 Segurança

O backend possui configuração utilizando Spring Security.

A segurança da aplicação é organizada em uma configuração específica dentro do projeto.

## 💻 Conceitos praticados

Durante o desenvolvimento deste projeto foram praticados conceitos como:

- Programação Orientada a Objetos
- Java
- Spring Boot
- APIs REST
- Spring Data JPA
- Hibernate
- Spring Security
- Arquitetura em camadas
- Controllers
- Services
- Repositories
- Entities
- Paginação
- Filtros por período
- Banco de dados
- Integração com serviço externo
- Maven

- ## 📚 Objetivo do projeto

O objetivo deste projeto foi aprofundar meus conhecimentos em desenvolvimento Backend com Java e Spring Boot.

Durante o desenvolvimento, foram praticados conceitos de criação de APIs REST, persistência de dados, organização em camadas, consultas paginadas, segurança e integração com serviços externos.

## 👨‍💻 Sobre o desenvolvimento

Este projeto faz parte dos meus estudos autodidatas de Java e desenvolvimento Backend.

O projeto foi desenvolvido com base na Semana Spring React da DevSuperior, sendo utilizado como prática para aprofundar meus conhecimentos em Java, Spring Boot, APIs REST, banco de dados e integração entre Backend e Frontend.

## 🔗 Autor

**Gabriel Silva**

GitHub: [GabrielDOSilva](https://github.com/GabrielDOSilva)
