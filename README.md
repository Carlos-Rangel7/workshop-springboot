# WorkShop Spring Boot

#  Sobre o Projeto
Este projeto é uma API RESTful construída com Spring Boot, JPA e Hibernate, seguindo as boas práticas de arquitetura e organização de código. 
O objetivo é fornecer um sistema de gerenciamento de usuários, pedidos e produtos, incluindo operações CRUD e tratamento de exceções.



# 📌 Objetivo
Criar um projeto Spring Boot em Java

Implementar modelo de domínio com entidades relacionadas

Estruturar as camadas lógica: resource, service e repository

Configurar banco de dados H2 para testes

Realizar operações CRUD (Create, Retrieve, Update, Delete)

Implementar tratamento de exceções



# ⚙ Tecnologias Utilizadas

Java 17

Spring Boot (Spring Web, Spring Data JPA)

Hibernate

H2 Database (ambiente de testes)

Maven



#  Endpoints Principais

| Método  | Endpoint      | Descrição                  |
|---------|-------------|----------------------------|
| **GET**    | `/users`      | Lista todos os usuários    |
| **GET**    | `/users/{id}` | Busca usuário por ID      |
| **POST**   | `/users`      | Cria um novo usuário      |
| **PUT**    | `/users/{id}` | Atualiza usuário por ID   |
| **DELETE** | `/users/{id}` | Remove usuário por ID     |

# Tratamento de Exceções

O projeto possui um sistema de tratamento de exceções global utilizando @ControllerAdvice. Algumas das exceções tratadas:

ResourceNotFoundException (Erro 404 - Recurso não encontrado)

DatabaseException (Erro 400 - Violação de integridade)
