# Regras de Negócio - Comanda Digital

## 1. Clientes

- O sistema deve permitir cadastrar, alterar e consultar clientes;
- Cada cliente deve possuir um identificador único;
- O nome do cliente é campo obrigatório;
- Clientes com pedidos registrados não devem ser excluídos do histórico;

## 2. Cardápio

- O sistema deve permitir cadastrar, alterar e consultar produtos;
- Cada produto deve possuir nome, descrição, preço e categoria;
- O preço do produto deve ser maior que zero;
- Produtos indisponíveis não podem ser adicionados a novos pedidos;

## 3. Mesas

- O sistema deve permitir cadastrar mesas;
- Cada mesa deve possuir um número e um status;
- Uma mesa opcupada não pode receber um novo atendimento;
- A mesa deve ser liberada após o encerramento do atendimento;

## 4. Pedidos

- O pedido deve possuir um identificador, data, status e itens;
- Um pedido presencial deve estar vinculado a uma mesa;
- Um pedido deve possuir pelo menos um item para ser finalizado;
- A quantidade de cada item deve ser maior que zero;
- O valor do item é calculado pela quantidade x preço;
- O valor total do pedido é a soma dos valores dos seus itens;
- Produtos indisponíveis não podem ser adicionados ao pedido;
- Pedidos finalizados devem permanecer no histórico;

## 5. Pagamento

- O sistema deve permitir registrar a forma de pagamento;
- O valor pago não pode ser menor que o valor do pedido;
- Quando o pagamento for em dinheiro, o sistema deve calcular o troco;
- Após o pagamento, o pedido poderá ser finalizado e a mesa liberada;

## 6. Funcionários

- O sistema deve permitir cadastrar funcionários;
- Funcionários devem possuir um identificador, nome e cargo;
- Funcionários inativos não devem realizar operações no sistema;

## 7. Delivery

Futuramente o sistema deverá permitir

- Pedidos para entrega;
- Cadastro de endereços;
- Taxa de entrega;
- Acompanhamento do status da entrega;