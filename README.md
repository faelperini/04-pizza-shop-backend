# Pizza Shop - Backend

## Descrição

Este back-end, construído com TypeScript, Drizzle e ElysiaJS, oferece uma visão completa e detalhada para gerenciar seu restaurante. Com ele, você terá acesso a métricas cruciais para tomar decisões estratégicas e otimizar suas operações.

## Funcionalidades

* **Análise de Vendas:**
  * Receita total por mês
  * Número de pedidos por mês e por dia
  * Análise de cancelamentos
  * Receita em períodos personalizados
* **Gestão de Produtos:**
  * Identificação dos produtos mais populares

## Executando

Este projeto depende do Docker para configurar o banco de dados. Com o Docker instalado, clone o projeto, instale as dependências, configure os contêineres do Docker e execute a aplicação.

Você também deve executar migrações para criar tabelas do banco de dados e executar o seed para popular o banco de dados com dados fictícios.

1. Clone o projeto:
```bash
  git clone https://github.com/faelperini/04-pizza-shop-backend
```
2. Abra o diretório
```bash
  cd 04-pizza-shop-backend
```

3. Instale as dependências:
```bash
  npm install
  bun install
```
4. Inicie os containers do Docker:
```bash
  docker compose up -d
```
5. Execute as migrações:
```bash
  npm run migrate
```
6. Popule o banco de dados:
```bash
  npm run seed
```
7. Inicie o servidor:
```bash
  npm run dev
```

## Autenticação

A autenticação é feita por meio de um link enviado no terminal de execução do backend após o cadastro ou login.
