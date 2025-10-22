# Projeto E-Commerce DIO
O projeto E-Commerce DIO, é um desafio do curso de SQL da DIO, onde estamos desenvolvendo um Projeto Conceitual de Banco de Dados para o modelo de E-Commerce.
Este documento do projeto descreve o desenvolvimento do modelo de banco de dados de um sistema de E-Commerce, abrangendo desde o diagrama inicial até as refinarias realizadas para atender aos novos requisitos do desafio.

# Diagrama Inicial:

O modelo inicial apresentava entidades principais como Cliente, Produto, Pedido, Estoque e Fornecedor.
____________

<img width="970" height="1057" alt="Projeto E-Commerce" src="https://github.com/user-attachments/assets/4bf77932-b0f4-43f1-8737-5cc1879a6af4" />

____________


# 🧱⚒️ Refinamentos Realizados:

No modelo refinado, foram adicionadas novas entidades, e ajustados relacionamentos para refletir melhor a estrutura de um sistema de E-Commerce realista. As principais mudanças foram:

#### Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações;
#### Pagamento – Pode ter cadastrado mais de uma forma de pagamento; 
#### Entrega – Possui status e código de rastreio;

# ⬆️ Modelo Atualizado:
 Abaixo está o diagrama atualizado, com as novas entidades e relacionamentos integrados ao
 modelo E-Commerce.

_______________

 <img width="990" height="1226" alt="Projeto E-Commerce_Refinado" src="https://github.com/user-attachments/assets/0210cc2d-aff4-4f62-a202-93f87d1e3547" />

_______________

### Relacionamentos de Chaves:

 • Cliente → Pessoa_Física (1:0..1)
 
 • Cliente → Pessoa_Jurídica (1:0..1)
 
 • Cliente → Pagamento (1:N)
 
 • Pedido → Pagamento (1:1)
 
 • Pedido → Entrega (1:1)
 
 • Pedido → Produto (N:M)

### 👏✅ Conclusão:

 O modelo final oferece uma representação robusta e flexível do sistema E-Commerce, permitindo o gerenciamento de clientes (PF e PJ), produtos, fornecedores, pedidos, pagamentos e entregas.

