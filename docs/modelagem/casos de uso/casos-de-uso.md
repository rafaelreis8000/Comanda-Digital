# Descrição dos Casos de Uso

## 1. Objetivo

Este documento descreve todas as interações e funcionalidades do projeto, separada por atores

## 2 Atores

Foram definidos atores no sistema com diferentes permissões, funções e atividades. Inicialmente três deles são base para o desenvolvimento das atividades do Sistema.

### 2.1 Administrador

É responsável por gerenciar o sistema e suas configurações

### **Principais Responsabilidades**

- Gerenciar usuários;
- Cadastrar funcionários;
- Alterar dados de usuário;
- Inativar usuário;
- Gerenciar categorias;
- Gerenciar produtos;
- Consultar clientes;
- Consultar pedidos;
- Consultar comandas;
- Gerenciar dados do restaurante;

### 2.2 Funcionário

É um usuário interno do restaurante. Utiliza a plataforma para administrar os pedidos dos clientes. É o principal ator do projeto, já que está em constante operação, unindo pedidos e clientes.

### **Principais Responsabilidades**

- Gerenciar comanda;
- Cadastrar cliente;
- Gerenciar pedidos;
- Solicitar pagamento;

### 2.3 Cliente

Representa a pessoa que consome os produtos dentro do estabelecimento. Na primeira versão não possui um acesso propriamente, sendo então um ator secundário. Possui cadastro para que pedidos sejam anexados a ele, portanto sua única responsabilidade é efetuar pagamento.