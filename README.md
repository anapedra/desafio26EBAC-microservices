# 🛍️ Ecommerce Microservices Architecture

> Distributed e-commerce platform built with Spring Boot 2.3.4, Java 11, and Docker, applying the architecture of independent microservices.

---

## ✅ Requisitos do Projeto

- Java 11 (Correto para Spring Boot 2.3.4)
- Spring Boot 2.3.4.RELEASE
- Spring Cloud Hoxton.SR8
- Maven 3.6+
- Docker
- MongoDB (para catálogo)
- PostgreSQL (para usuários, pedidos e estoque)
- Git & GitHub
- IDE recomendada: VSCode ou IntelliJ IDEA

---

## 📌 Visão Geral

Este projeto é uma aplicação e-commerce moderna baseada em microserviços, organizada com foco em separação de responsabilidades, escalabilidade horizontal e comunicação via REST.

A arquitetura é composta por:

- 🔐 auth-service – Autenticação e autorização via JWT + OAuth2  
- 📦 catalog-service – Catálogo de produtos e categorias com MongoDB  
- 🧾 order-service – Gerenciamento de pedidos com PostgreSQL  
- 🧮 inventory-service – Controle de estoque  
- 🌐 api-gateway – Roteamento central com Zuul  
- 🧭 eureka-server – Registro e descoberta de serviços  
- ⚙️ config-server – Configuração centralizada via Spring Cloud Config


![Estrutura da arquitetura](https://drive.google.com/file/d/18ydWvkmf1_pGn4Lgw8EFyLnXu1rVDd0N/view?usp=sharing)


