# Sistema de Biblioteca

Este projeto é um sistema básico de gestão de biblioteca, que inclui a criação e manipulação de um banco de dados para armazenar informações sobre autores, livros e empréstimos.

## Estrutura do Banco de Dados

O banco de dados é composto pelas seguintes tabelas:

- **Autores**: Armazena informações sobre autores.
- **Livros**: Armazena informações sobre livros, incluindo o autor e o gênero.
- **Emprestimos**: Registra os empréstimos de livros, incluindo o nome do usuário e as datas de empréstimo e devolução.

## Passos para Configuração

1. **Criar o Banco de Dados**

   Execute o código SQL para criar o banco de dados e as tabelas necessárias.

   ```sql
   DROP DATABASE IF EXISTS Biblioteca;
   SET SQL_SAFE_UPDATES = 0;
   CREATE DATABASE Biblioteca;
   USE Biblioteca;

