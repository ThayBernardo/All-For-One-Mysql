<h1 align="center">All For One</h1>

# Sobre

Aplicação utilizando o banco de dados `Northwind`, utilizando informações dele com `queries` SQL.

- SQL
- Docker

# O que foi desenvolvido

- Filtragem de dados.
- Acesso de informações.
- Manipulação de tabelas.

# Features

- [x] Nomes dos produtos na tabela `products`.
- [x] Dados de todas as colunas da tabela `products`.
- [x] Valores da coluna que representa a primary key da tabela `products`.
- [x] Conta quantos registros existem na coluna `product_name` da tabela `products`.
- [x] Dados da tabela `products` a partir do quarto registro até o décimo terceiro.
- [x] Dados das colunas `product_name` e `id` da tabela `products` com os resultados em ordem alfabética dos nomes.
- [x] Ids dos 5 últimos registros da tabela `products`.
- [x] Retorna três colunas,com os nomes 'A', 'Trybe' e 'eh', e com valores referentes a soma de '5 + 6', a string 'de', a soma de '2 + 8'.
- [x] Valores de `notes` da tabela `purchase_orders` que não são nulos;
- [x] Dados da tabela `purchase_orders` em ordem decrescente, ordenados por `created_by` em que o `created_by` é maior ou igual a 3.
- [x] Dados da coluna `notes` da tabela `purchase_orders` em que seu valor de Purchase generated based on Order é maior ou igual a 30 e menor ou igual a 39.
- [x] `submitted_date` de `purchase_orders` em que a `submitted_date` é do dia 26 de abril de 2006.
- [x] `supplier_id` das `purchase_orders` em que o `supplier_id` seja 1 ou 3.
- [x] Resultados da coluna `supplier_id` da tabela `purchase_orders` em que o `supplier_id` seja maior ou igual a 1 e menor ou igual 3.
- [x] Horas (sem os minutos e os segundos) da coluna `submitted_date` de todos registros da tabela `purchase_orders`.
- [x] `submitted_date` das `purchase_orders` que estão entre 2006-01-26 00:00:00 e 2006-03-31 23:59:59.
- [x] Registros das colunas `id` e `supplier_id` das `purchase_orders` em que os `supplier_id` sejam tanto 1, ou 3, ou 5, ou 7.
- [x] Registros de `purchase_orders` que tem o `supplier_id` igual a 3 e `status_id` igual a 2.
- [x] Quantidade de pedidos que foram feitos na tabela `orders` pelo `employee_id` igual a 5 ou 6, e que foram enviados através do método(coluna) `shipper_id` igual a 2.
- [x] Adiciona dados à tabela `order_details`.
- [x] Adiciona duas linhas à tabela `order_details` com um único `INSERT`.
- [x] Atualiza os dados de `discount` do `order_details`.
- [x] Atualiza os dados da coluna `discount` da tabela `order_details`, onde o valor na coluna `unit_price` seja menor que 10.0000.
- [x] Atualiza os dados da coluna `discount` da tabela `order_details`, onde o valor na coluna `unit_price` seja maior que 10.0000 e o `id` seja um número entre 30 e 40.
- [x] Deleta todos os dados em que a `unit_price` da tabela `order_details` seja menor que 10.0000.
- [x] Deleta todos os dados em que a `unit_price` da tabela `order_details` seja maior que 10.0000.
- [x] Deleta todos os dados da tabela `order_details`.

# Rodando em Docker
<strong>É necessário que você tenha em sua máquina instalado `node` e `docker`</strong>

>Rode o serviço `node` com o comando:

```bash
docker-compose up -d
``` 

- Esse serviço irá inicializar um container chamado all_for_one  e outro chamado all_for_one_db.
- A partir daqui você pode rodar o container via CLI ou abri-lo no VS Code.

>Use o comando:

```bash
docker exec -it all_for_one bash
```

- Ele te dará acesso ao terminal interativo do container criado pelo compose, que está rodando em segundo plano.

>Instale as dependências com:

```bash
npm install
```

# Rodando localmente

>Instale as dependências com:

```bash
npm install
```