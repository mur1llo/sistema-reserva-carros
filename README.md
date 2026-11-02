# -Sistema de Reserva de Carros

## -Visão Geral

O objetivo é implementar a estrutura de um banco de dados para um sistema de reserva de veículos, utilizando MySQL para organizar informações sobre clientes, carros, sedes, classes de veículos e reservas.

O projeto permite praticar conceitos de modelagem de bancos de dados relacionais, criação de tabelas, definição de chaves primárias e estrangeiras e estabelecimento de relacionamentos entre entidades.

## -Tecnologias Utilizadas

- **MySQL:** sistema de gerenciamento de banco de dados.
- **SQL:** linguagem utilizada para criação e manipulação dos dados.
- **MySQL Workbench:** ferramenta para execução e gerenciamento do banco de dados.

## -Estrutura do Banco de Dados

O banco de dados é composto por cinco tabelas principais:

- `sedes`: informações sobre as unidades da empresa.
- `classesCarro`: categorias dos veículos e valores das diárias.
- `clientes`: cadastro e informações dos clientes.
- `carros`: informações dos veículos disponíveis.
- `reservas`: registros relacionados às reservas de carros.

### Relacionamentos

O projeto utiliza chaves primárias (PRIMARY KEY) e chaves estrangeiras (FOREIGN KEY) para estabelecer os relacionamentos entre as tabelas.

## -Como Executar o Projeto

1. Instale o MySQL e o MySQL Workbench.
2. Clone este repositório:

   ```bash
   git clone https://github.com/Mur1llo/sistema-reserva-carros.git
   ```

3. Abra o MySQL Workbench.
4. Abra o arquivo `database.sql`.
5. Execute o script SQL.
6. Verifique a criação das tabelas utilizando:

   ```sql
   USE AcdnRentalCar;
   SHOW TABLES;
   ```

## -Objetivo Acadêmico

Desenvolver conhecimentos práticos em modelagem e gerenciamento de bancos de dados relacionais, aplicando conceitos fundamentais da linguagem SQL.

## -Autor

**Murillo Cardoso Mendes**

- GitHub:https://github.com/Mur1llo
- LinkedIn:https://www.linkedin.com/in/murillo-cardoso-29590a430/

- Imagem do projeto::

- <img width="1359" height="729" alt="image" src="https://github.com/user-attachments/assets/8886cc61-c7af-4988-b49e-ec196a7b0cfe" />
 
