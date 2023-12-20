# Projeto Java JDBC

## Descrição

Este projeto demonstra um exemplo simples de como usar JDBC (Java Database Connectivity) para interagir com um banco de dados. Ele inclui operações básicas CRUD (Create, Read, Update, Delete) para as entidades `Department` e `Seller`.

## Estrutura do Projeto

- **application**: Classes principais para executar testes.
  - `Program.java`: Testes relacionados aos vendedores.
  - `Program2.java`: Testes relacionados aos departamentos.
  
- **model.dao**: Interfaces DAO.
  - `DepartmentDao.java`: Interface para operações do departamento.
  - `SellerDao.java`: Interface para operações do vendedor.
  
- **model.dao.impl**: Implementações concretas das interfaces DAO.
  - `DepartmentDaoJDBC.java`: Implementação para `Department`.
  - `SellerDaoJDBC.java`: Implementação para `Seller`.

- **model.entities**: Classes de entidades.
  - `Department.java`: Representa um departamento.
  - `Seller.java`: Representa um vendedor.
  
- **model.dao**: Fábrica para criação de DAOs.
  - `DaoFactory.java`: Cria instâncias dos DAOs.

- **db**: Conexão com o banco de dados.
  - `DB.java`: Classe para obter a conexão com o banco de dados.

## Como Executar

1. Clone o repositório.
2. Instale o MySQL Connector/J no seu projeto.
3. Configure as informações de conexão no arquivo `db/DB.java`.
4. Execute os testes nas classes `Program.java` e `Program2.java`.

## Funcionalidades Principais

### Para `Seller`:

- Busca por ID.
- Busca por departamento.
- Listagem de todos.
- Inserção.
- Atualização.
- Exclusão.

### Para `Department`:

- Busca por ID.
- Listagem de todos.
- Inserção.
- Atualização.
- Exclusão.

## Tecnologias Utilizadas

- Java
- JDBC
- MySQL (ou outro banco de dados)

## Conclusão

Este projeto serve como um exemplo básico de como usar JDBC em um projeto Java para operações de banco de dados. Sinta-se à vontade para explorar, modificar e expandir conforme necessário.
