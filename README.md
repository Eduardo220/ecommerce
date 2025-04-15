# Refinando um design conceitual de banco de dados
Primeiro desafio de projeto do curso "SQL Database Specialist" da [DIO](https://www.dio.me/).

### 💵 E-commerce
Entidades: Produto, Estoque, Fornecedor, Pedido, Cliente.

### 📖 História
CPF: CPF (Cadastro de Pessoas Físicas) é um número de identificação de contribuintes emitido pela Receita Federal do Brasil. É um número de 11 dígitos usado para identificar pessoas físicas para fins fiscais, financeiros e legais. <br>

CNPJ: CNPJ (Cadastro Nacional da Pessoa Jurídica) é um número de identificação empresarial emitido pela Receita Federal do Brasil. É usado para identificar pessoas jurídicas (empresas, organizações e outras entidades comerciais) para fins fiscais, financeiros e regulatórios.

#### 1. Produto

Os produtos são vendidos por meio de uma única plataforma online. No entanto, podem ter vendedores diferentes (terceiros).

Cada produto possui um fornecedor.

Um pedido pode conter um ou mais produtos.

#### 2. Cliente

O cliente pode se cadastrar no site com seu CPF ou CNPJ.

O endereço do cliente determinará o custo do frete.

Um cliente pode realizar mais de um pedido. Estes possuem um prazo de devolução.

#### 3. Pedido

Os pedidos são criados pelos clientes e contêm informações de compra, endereço e status da entrega.

O pedido pode ser cancelado.

Um pedido pode conter um ou mais produtos.

### 💻 Descrição do desafio
Refine o modelo apresentado adicionando os seguintes pontos:

Os clientes podem criar uma conta individual ou empresarial, mas essa conta não pode conter ambas as informações.

O cliente pode cadastrar mais de um método de pagamento.

A entrega possui status e código de rastreamento.

### ✅ Solução
<img align="center" src="https://github.com/Eduardo220/ecommerce/blob/main/e-commerce.png" width=""/> 

## 🛠️ Minhas tecnologias
<p align="center">

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg" width="100">   
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mysql/mysql-original.svg" width="100">      

</p> 
