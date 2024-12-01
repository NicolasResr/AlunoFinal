# API de Cadastro de Alunos - Java 21 + Spring Boot

Este projeto é uma API RESTful para o cadastro de alunos, desenvolvida em **Java 21** utilizando **Spring Boot** para a parte backend. A aplicação utiliza o **Aiven (MySQL)** como banco de dados, e inclui um frontend simples utilizando **HTML**, **CSS** e **JavaScript** para a interação do usuário.

## Tecnologias Utilizadas

- **Java 21** (JDK 21)
- **Spring Boot** (Framework para construção de APIs REST)
- **Aiven (MySQL)** (Banco de dados na nuvem)
- **HTML** (Estrutura do frontend)
- **CSS** (Estilos do frontend)
- **JavaScript** (Interatividade no frontend e conectar o front com o backend)
- **Maven** (Gerenciador de dependências e construção do projeto)

## Funcionalidades da API

A API permite realizar as operações CRUD (Criar, Ler, Atualizar, Excluir) sobre o cadastro de alunos.

- **Cadastrar aluno**: Adicionar novos alunos ao banco de dados.
- **Listar alunos**: Obter uma lista de todos os alunos cadastrados.
- **Buscar aluno**: Consultar informações de um aluno específico.
- **Atualizar aluno**: Modificar as informações de um aluno existente.
- **Excluir aluno**: Remover um aluno do banco de dados.

## Endpoints da API

### 1. **Cadastrar aluno**
- **Método**: `POST`
- **URL**: `/a/p`
- **Body (JSON)**:
  ```json
  {
        "user": "vitor",
        "telefone": "119232032",
        "email": "vitor@gmail.com",
        "imagemUrl": "https://i.pinimg.com/236x/eb/d8/4d/ebd84de163395907482a2e0eba978ea3.jpg"
  }
### 2. **Atualizar aluno**
- **Método**: `PUT`
- **URL**: `/a/{id}`
- **Body (JSON)**:
  ```json
  {
        "user": "jorge",
        "telefone": "119232032",
        "email": "madeira@gmail.com",
        "imagemUrl": "https://i.pinimg.com/236x/eb/d8/4d/ebd84de163395907482a2e0eba978ea3.jpg"
  }

### 3. **Deletar aluno**
- **Método**: `DELETE`
- **URL**: `/a/{id}`

### 4. **Buscar aluno**
- **Método**: `GET`
- **URL**: `/a

 
