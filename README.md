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

## Sprint 8: Documentação e Deploy
### O que foi feito:

- Documentação com Swagger (OpenAPI)

- Deploy no Render/Vercel

- Monitoramento inicial

### Desenvolvedores:

- Ana: Criou documentação.

- Marcelo: Configurou deploy.

### Períodos:

- Desenvolvimento: 2 dias

- Deploy: 1 dia

- Data: 16/10/2025 - 20/10/2025


## Sprint 9: Página Inicial
### O que foi feito:

- Desenvolvimento de 2 seções (Hero e amostra de produtos) da página inicial e integração

### Desenvolvedores:

- Ana:  Criou os componentes de cards de produtos.

- Marcelo: Integrou os dados da API.

### Períodos:

- Desenvolvimento: 3 dias

- Testes: 1 dia

- Data: 21/10/2025 - 27/10/2025

## Sprint 10: Página de Listagem dos Produtos
### O que foi feito:

- Carrossel de imagens, seleção de cor/tamanho, botão "Add to Cart"

- Seção de produtos relacionados

### Desenvolvedores:

- Ana: Implementou lógica de seleção de atributos.

- Marcelo: Desenvolveu o carrossel e layout.

### Períodos:

- Desenvolvimento: 4 dias

- Testes: 2 dia

- Data: 28/10/2025 - 04/11/2025

## Sprint 11: Configuração do estado do carrinho com Redux
### O que foi feito:

- Listagem de itens com ajuste de quantidade/remoção

- Cálculo dinâmico de subtotal/total

- Botões "Checkout" e "Continue Shopping"

### Desenvolvedores:

- Ana: Integrou carrinho com Redux.

- Marcelo: Desenvolveu a função para contagem de produtos no carrinho no header.

### Períodos:

- Desenvolvimento: 4 dias

- Testes: 1 dia

- Data: 05/11/2025 - 11/11/2025

## Sprint 12: Tela de checkout
### O que foi feito:

- Formulário de endereço com validação de CEP (API ViaCEP)

- Blocos de subtotal/total e botão "Place Order"

### Desenvolvedores:

- Ana: Implementou validação de CEP e formulário.

- Marcelo: Desenvolveu a função e layout do checkout

### Períodos:

- Desenvolvimento: 5 dias

- Testes: 2 dia

- Data: 12/11/2025 - 21/11/2025

## Sprint 13: Página de Pós-Pagamento
### O que foi feito:

- Página "After Payment" com mensagem de sucesso

- Redirecionamento + botão “Go to My Account”.

### Desenvolvedores:

- Ana: Desenvolveu a página de pós-pagamento.

- Marcelo: Redirecionamento + estidos do botão “Go to My Account”.

### Períodos:

- Desenvolvimento: 4 dias

- Testes: 1 dia

- Data: 24/11/2025 - 28/11/2025

## Sprint 14: Profile - Parte 1 (Detalhes da conta)
### O que foi feito:

- Layout da página de profile

- Função para buscar os pedidos já feitos pelo usuário no banco de dados

### Desenvolvedores:

- Ana: Página com avatar, nome e e-mail.

- Marcelo: Logout e validação de sessão com clerk.

### Períodos:

- Desenvolvimento: 4 dias

- Testes: 1 dia

- Data: 24/11/2025 - 28/11/2025

## Sprint 15: Profile - Parte 2 (Pedidos)
### O que foi feito:

- Função para listegem dos pedidos vindos do back-end

### Desenvolvedores:

- Ana: Listagem de pedidos feitos.

- Marcelo: Botão "view item" redirecionando para Product.

### Períodos:

- Desenvolvimento: 4 dias

- Testes: 1 dia

- Data: 24/11/2025 - 28/11/2025


## Sprint 16: Página About
### O que foi feito:

- Página "About" com foto, descrição e contatos

- Página 404 personalizada

### Desenvolvedores:

- Ana: Layout com a foto do fornecida pelo usuário, descrição e contatos.

- Marcelo: Integração com o layout geral do site (header/footer).

### Períodos:

- Desenvolvimento: 2 dias

- Testes: 1 dia

- Data: 01/12/2025 - 03/11/2025

## Sprint 17: Página 404
### O que foi feito:

- Página customizada para rotas inexistentes

- Página 404 personalizada

### Desenvolvedores:

- Ana: Layout e integração com estilo do Figma.

- Marcelo: Redirecionamento de links inválidos no Footer.

### Períodos:

- Desenvolvimento: 2 dias

- Data: 01/12/2025 - 02/11/2025


