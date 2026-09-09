# Atores do Sistema

## 1. Atores Principais

### 1.1 Administrador

Responsável pelo gerenciamento do sistema. Tem permissão de configurar a estrutura do restaurante

#### Responsabilidades

- Cadastrar usuário;
- Alterar e excluir usuário;
- Cadastrar categoria de produto;
- Cadastrar produtos no cardápio;
- Alterar informações de produto;
- Remover/ desativar produtos;
- Consultar clientes;
- Consultar pedidos;
- Gerenciar dados do restaurante (nome, endereço...);

#### Principais Interações

- Gerenciar usuários;
- Gerenciar cardápio;
- Gerenciar categorias;
- Consultar clientes;
- Consultar pedidos;
- Consultar comandas;

### 1.2 Garçom

Possui contato direto com os clientes. pode ser tratado também simplesmente como "Funcionário"

#### Responsabilidades

- Visualizar cliente;
- Cadastrar cliente;
- Abrir comanda;
- Designar mesa;
- Adicionar produtos;
- Alterar quantidade;
- Remover produtos;
- Visualizar cardápio;
- Enviar pedido;
- Visualizar status do pedido;
- Consultar valor da comanda;
- Encerrar comanda;

#### Principais interações

- Cadastrar cliente;
- Consultar cliente;
- Abrir comanda;
- Criar pedido;
- Adicionar itens;
- Alterar pedido;
- Visualizar status;
- Consultar comanda;

### 1.3 Cliente

Inicialmente não possui acesso à plataforma, só possuindo esse controle em futuras versões com delivery

#### Responsabilidades

- Fornecer dados para cadastro quando necessário;
- Consultar cardápio;
- Fazer pedidos;
- Consultar pedidos;
- Visualizar status do pedido;
- Consultar consumo da comanda;

#### Principais interações

- Cadastro;
- COnsulta do cardápio;
- Realização de pedido;
- Consulta de pedido;
- Consulta da comanda;

## 2. Atores Secundários

### 2.1 Sistema de Pagamento

Inicialmente não faz parte do sistema, podendo ser integrado futuramente. Seu uso não é obrigatório na primeira versão

#### Responsabilidades

- Processar pagamentos;
- Validar transações;
- Retornar o resultado do pagamento;
- Informar aprovação ou recusa;

### 2.2 Sistema de delivery

Também uma futura integração do projeto, permite que pedidos sejam feitos pelo cliente em seu endereço

#### Responsabilidades

- Receber pedidos;
- Enviar informações do pedido;
- Atualizar o status da entrega;