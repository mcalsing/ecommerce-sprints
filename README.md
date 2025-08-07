# Sprints para E-commerce

## Sprint 1: Configuração Inicial e Ambiente
### O que foi feito:

- Criação do repositório, estrutura inicial do projeto com Vite.js + TypeScript, instalação do Tailwind, Clerk, Redux Toolkit e configuração básica de rotas.

### Desenvolvedores:

- Ana: Setup do Vite.js, Tailwind e estrutura de pastas.

- Marcelo: Implementou Redux/Context API e rotas base.

### Períodos:

- Desenvolvimento: 3 dias

- Testes: 1 dia

- Revisão: 1 dia

- Deploy: 1 dia

- Data: 01/09/2025 - 06/09/2025

## Sprint 2: Telas de Login, Criação do usuário e Autenticação (Clerk)
### O que foi feito:

- Tela de login, tela de cadastro, configurações do dashboard do clerk e fluxo de autenticação com Clerk.

### Desenvolvedores:

- Ana: Configuração do dashboard e implementação do fluxo de autenticação com Clerk.

- Marcelo: Criou telas de login e cadastro responsivas.

### Períodos:

- Desenvolvimento: 4 dias

- Testes: 2 dia

- Revisão: 1 dia

- Data: 07/09/2025 - 14/09/2025

## Sprint 3: Componentes Header e Footer
### O que foi feito:

- Header com logo, menu, carrinho e ícone de perfil dinâmico

- Footer com newsletter (validação de e-mail), links e copyright dinâmico

### Desenvolvedores:

- Ana: Implementou lógica do carrinho e perfil.

- Marcelo: Desenvolveu footer e integração da newsletter.

### Períodos:

- Desenvolvimento: 4 dias

- Testes: 1 dia

- Data: 15/09/2025 - 20/09/2025

## Sprint 4: Configuração Inicial e Modelagem do Back-end
### O que foi feito:

- Criação da base do projeto e definir os schemas do banco de dados

- Configuração do projeto Node.js (Express, Mongoose, dotenv)

  - Produto (nome, preço, estoque, categorias e imagem)
  - Order (produtos, usuário, endereço, status, total)

- Conexão com o banco de dados (MongoDB Atlas)

### Desenvolvedores:

- Ana: Configurou o ambiente e schemas.

- Marcelo: Implementou a conexão com o MongoDB.

### Períodos:

- Desenvolvimento: 3 dias

- Testes: 1 dia

- Data: 21/09/2025 - 25/09/2025

## Sprint 5: Método GET de Produtos
### O que foi feito:

- Desenvolvido endpoints de listagem e filtros de produtos.

- GET /api/products:

  - Listagem paginada
  - Filtros por categoria, preço máximo e busca por nome

- Validação de queries com Joi

### Desenvolvedores:

- Ana: Implementou paginação e filtros.

- Marcelo: Criou validações de queries.

### Períodos:

- Desenvolvimento: 4 dias

- Testes: 2 dias (Postman/unitários)

- Data: 26/09/2025 - 03/10/2025


## Sprint 6: Método POST de Pedidos
### O que foi feito:

- Criado endpoint para registrar pedidos.

- POST /api/orders:

  - Validação do corpo (produtos, usuário, endereço)
  - Cálculo automático do total com taxas.
  - Atualização do estoque dos produtos.

- Validação de queries com Joi

### Desenvolvedores:

- Ana: Lógica de cálculo do pedido.

- Marcelo: Integração com o schema de Order.

### Períodos:

- Desenvolvimento: 5 dias

- Testes: 2 dias (validação de estoque, erros)

- Data: 06/10/2025 - 14/10/2025

## Sprint 7: Integração com Front-end e Correções
### O que foi feito:

- Adição de CORS e headers de segurança

- Ajuste no GET /api/products para incluir campos exigidos pelo front (ex.: inStock)

- Middleware de erro padronizado

### Desenvolvedores:

- Ana: Configurou CORS e segurança.

- Marcelo: Adaptou responses para o front.

### Períodos:

- Desenvolvimento: 3 dias

- Testes: 2 dias (integração front-back)

- Data: 15/10/2025 - 12/10/2025




-----------------------------------------------------
## Sprint 4: Página Inicial
### O que foi feito:

- Desenvolvimento de 4 seções da página inicial e integração

### Desenvolvedores:

- Ana: Implementou lógica do carrinho e perfil.

- Marcelo: Desenvolveu footer e integração da newsletter.

### Períodos:

- Desenvolvimento: 4 dias

- Testes: 1 dia

- Data: 15/09/2025 - 20/09/2025