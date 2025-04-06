# 🍔 Bem-vindo ao **Tech Snack - Fast Food**!

 Esta organização centraliza os projetos desenvolvidos durante o Tech Challenge da pós-graduação em Arquitetura de Software da FIAP. 
 Abaixo, você encontrará uma visão geral dos projetos que compõem o sistema de autoatendimento para lanchonetes.

## 📂 Projetos

### 1. fastfood-infra
Provisionamento da infraestrutura necessária para o sistema de autoatendimento de fast food utilizando Terraform e serviços de nuvem AWS.

- **Módulos Terraform:** Cognito, Compute (EKS), Database (RDS), Gateway (API Gateway), Lambda
- **Objetivo:** Criar uma infraestrutura escalável e automatizada para suportar o sistema de pedidos

[Mais detalhes](https://github.com/tech-snack-fiap-soat-tech-challenge/fastfood-infra)

### 2. fiap-fast-food
Sistema de controle de pedidos para lanchonetes, projetado para melhorar a eficiência e a satisfação do cliente através de um sistema de autoatendimento.

- **Tecnologias:** Node.js, Docker, PostgreSQL
- **Funcionalidades:** Gestão de pedidos, pagamento via QR Code, painel administrativo

[Mais detalhes](https://github.com/tech-snack-fiap-soat-tech-challenge/fiap-fast-food)

### 3. fastfood-auth-lambda
Lambda de autenticação para o sistema de pedidos de fast food. Este projeto gerencia o fluxo de registro e login de usuários utilizando Amazon Cognito e CPF como identificador único.

- **Tecnologias:** Node.js, Amazon Cognito, AWS Lambda
- **Funcionalidades:** Cadastro e login de usuários via CPF, geração de token JWT

[Mais detalhes](https://github.com/tech-snack-fiap-soat-tech-challenge/fastfood-auth-lambda)



