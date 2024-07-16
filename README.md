# Universe Database

###### Technologies:
<p align="center">
<img src="https://img.icons8.com/color/75/000000/postgreesql.png" width="75" height="75" alt="PostgreSQL" style="margin: 10px 15px 0 15px;" />
</p>

- **PostgreSQL:** Utilizado para a criação e manipulação do banco de dados relacional.

## Descrição

Este projeto é um banco de dados relacional simples chamado "universe", projetado para armazenar informações sobre galáxias, estrelas, planetas e luas. Ele inclui funcionalidades para a criação de tabelas, definição de restrições e relacionamentos entre as tabelas através de um script SQL.

## Estrutura do Projeto

### Script SQL

O script `universe.sql` serve como a interface para criar o banco de dados e as tabelas. As principais funcionalidades incluem:

- Criação do banco de dados 'universe'.
- Definição de várias configurações para a sessão atual do banco de dados.
- Criação de várias tabelas no esquema público do banco de dados.
- Adição de várias restrições às tabelas, incluindo restrições de chave primária (PRIMARY KEY), restrições de chave única (UNIQUE) e restrições de chave estrangeira (FOREIGN KEY).

#### Benefícios do Uso do PostgreSQL

- **Facilidade de Uso:** Utiliza interfaces de linha de comando familiares para a rápida criação de bancos de dados.
- **Portabilidade:** Os scripts SQL podem ser executados em qualquer sistema baseado em Unix sem a necessidade de qualquer software adicional.

## Como Usar

### Executando o Script SQL

1. **Conecte-se ao PostgreSQL**: Conecte-se ao seu servidor PostgreSQL usando o comando `psql`.
2. **Execute o Script**: Inicie a criação do banco de dados executando o script com o comando `\i universe.sql`.

### Navegação dentro do Script

- **Menu Principal**:
  - O script automaticamente começa a criação do banco de dados e das tabelas quando é executado.

---
#### Este é um desafio do FreeCodeCamp para a certificação de Projetos de Banco de Dados Relacionais

<p align="center">
<img src="https://cdn.freecodecamp.org/platform/universal/fcc_primary.svg" width="250" height="75" alt="freeCodeCamp" style="margin: 0 15px; opacity: 0.6" />
</p>
