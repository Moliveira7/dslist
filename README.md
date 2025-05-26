# 🎮 DSList API

O **DSList** é uma aplicação backend desenvolvida em **Java 17** com **Spring Boot**, que oferece uma **API REST** para gerenciamento de listas de jogos. Este projeto foi realizado como parte de um intensivão de Java com foco em boas práticas, arquitetura RESTful e uso de **Spring Data JPA** para persistência de dados.

---

## 🚀 Tecnologias e Ferramentas

- Java 17
- Spring Boot 3.4.6
- Spring Data JPA
- PostgreSQL (ou H2 para testes)
- Maven
- Lombok (dependência opcional, se utilizada)

---
## 📊 Funcionalidades

✅ Listar todos os jogos cadastrados  
✅ Listar todas as listas de jogos  
✅ Buscar detalhes de um jogo específico  
✅ Atualizar a posição de um jogo em uma lista  
✅ Ordenar os jogos em uma lista

---

## 🔗 Endpoints REST (exemplo)

| Método | Endpoint                                | Descrição                                |
|--------|------------------------------------------|------------------------------------------|
| GET    | `/games`                                 | Lista todos os jogos                      |
| GET    | `/games/{id}`                             | Busca detalhes de um jogo específico      |
| GET    | `/lists`                                  | Lista todas as listas de jogos           |
| GET    | `/lists/{id}`                             | Busca detalhes de uma lista específica    |
| POST   | `/lists/{listId}/replacement`             | Atualiza a ordem dos jogos na lista       |

---

## 🏗️ Como rodar o projeto

### Pré-requisitos

- Java 17
- Maven
- PostgreSQL (ou H2 para testes)