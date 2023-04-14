# demo-dao-jdbc

Este é um projeto de exemplo que utiliza o padrão de acesso a dados DAO (Data Access Object) em conjunto com o JDBC (Java Database Connectivity) para realizar operações de CRUD (Create, Read, Update, Delete) em um banco de dados MySQL.

## Como utilizar

1. Crie um banco de dados MySQL e configure as informações de conexão no arquivo `db.properties`.

2. Execute o script SQL localizado em `src/main/resources/db/create_db.sql` para criar a estrutura do banco de dados.

3. Execute o script SQL localizado em `src/main/resources/db/populate_db.sql` para popular o banco de dados com dados de exemplo.

4. Execute o projeto em sua IDE de escolha.

## Funcionalidades

O projeto demonstra as seguintes funcionalidades:

- Consulta de todos os departamentos
- Consulta de um departamento por ID
- Inserção de um novo departamento
- Atualização de um departamento existente
- Exclusão de um departamento existente

## Tecnologias utilizadas

- Java 8+
- MySQL
- JDBC

## Como contribuir

1. Faça um fork deste repositório.

2. Crie uma nova branch com a feature que você deseja implementar.

3. Faça suas alterações e commit.

4. Envie um pull request para este repositório.

## Autor

* **Israel Machado** - [israel-machado](https://github.com/israel-machado)

## Agradecimentos

Este projeto foi desenvolvido como parte do curso [Java COMPLETO Programação Orientada a Objetos + Projetos](https://www.udemy.com/course/java-curso-completo/).
