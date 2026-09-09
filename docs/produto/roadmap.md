# Roadmap - Comanda Digital

## 1. Fase 1 - Planejamento

- Definir o objetivo e o escopo do sistema;
- Levantar Requisitos Funcionais;
- Levantar requisitos não funcionais;
- Identificar usuários e permissões
- Definir regras de negócio;
- Criar Backlog inicial;
- Definir metodologia Scrum;
- Definir tecnologias e bibliotecas;

**Resultado:** Visão gerla do sistema e o backlog do projeto

## 2. Fase 2 - Modelagem

- Modelar entidades do sistema;
- Definir relacionamentos;
- Criar diagrama de classes;
- Definir arquitetura do sistema;
- Modelar banco de dados;
- Criar modelo entidade-relacionamento;
- Definir API e contratos;
- Documentar decisões arquiteturais;

**Resultado:** Estruturação técnica para implementação

## 3. Fase 3 - Backend

### 3.1 Estrutura Inicial

- Criar projeto;
- Configurar dependências;
- Configurar banco de dados;
- Criar estrutura de pacotes;
- Configurar ambiente de desenvolvimento;

### 3.2 Domínio

- Implementar Cliente;
- Implementar Produto;
- Implementar Categoria;
- Implementar Pedido;
- Implementar ItemPedido;
- Implementar Mesa;
- Implementar Usuário;
- Implementar demais entidades necessárias;

### 3.3 Funcionalidades

- Cadastro de clientes;
-Cadastro de categorias;
- Cadastro de produtos;
- Controle de mesas;
- Abertura de comandas;
- Inclusão de produtos na comanda;
- Alteração de pedidos;
- Cancelamento de itens;
- Fechamento da comanda;
- Consulta de pedidos;
- Controle de usuários e permissões;

### 3.4 API

- Criar endpoints;
- Implementar validações;
- Implementar tratamento de erros;
- Implementar regras de negócio;
- Documentar API;
- Testar endpoints;

**Resultado:** backend funcional disponibilidando os serviços da aplicação

## 4. Fase 4 - Frontend Web

### 4.1 Estrutura

- Criar projeto frontend;
- Definir estrutura de componentes;
- Criar sistema de navegação;
- Criar layout de tela;
- Definir identidade visual;

### 4.2 Telas

- Login;
- Dashboard;
- Clientes;
- Cardápio;
- Categorias;
- Mesas;
- Comandas;
- Pedidos;
- Fechamento de comanda;
- Usuários;
- Configurações;

### 4.3 Integração

- Integrar frontend com API;
- Implementar autenticação;
- Implementar controle de sessão;
- Tratar erros da API;
- Validar formulários;
- Testar fluxo completo;

**Resultado:** Sistema web para desktop e mobile

## 5. Fase 5 - MVP

### Funcionalidades do MVP

- Login;
- Cadastro de produtos;
- Cadastro de categorias;
- Cadastro de clientes;
- Cadastro de mesas;
- Abertura de comanda;
- Inclusão de produtos;
- Alteração de pedidos;
- Remoção/ Cancelamento de itens;
- Fechamento de comanda;
- Consulta de pedidos;

**Resultado:** primeira versão utilizável do sistema

## 6. Fase 6 - Testes e Qualidade

- Criar testes unitários;
- Criar testes de integração;
- Testar API;
- Testar interface;
- Testar responsividade;
- Testar permissões;
- Testar tratamento de erros;
- Corrigir bugs;
- Realizar testes de aceitação

**Resultado:** Versão validada e preparada para implantação

## 7. Fase 7 - Deploy

- Configurar ambiente de produção;
- Configurar banco de dados de produção;
- Configurar backend;
- Configurar frontend;
Configurar variáveis de ambiente;
- COnfigurar domínio;
- Configurar HTTPS;
- Criar rotina de backup;
- Monitorar aplicação;

**Resultado:** Sistema disponível em ambiente de produção

## 8. Fase 8 - Melhorias

### Novas funcionalidades podem ser adicionadas após a validação do MVP

- Relatório de vendas;
- Relatório de produtos;
- Histórico de comandas;
- Dashboard gerencial;
- Controle de estoque;
- Impressão de pedidos;
- Integração com impressoras;
- Controle financeiro;
- Diferentes formas de pagamento;
- Permissões avançadas;
- Auditoria de operações;

## 9. Fase 9 - Suporte a Delivery

Implementação de suporte a delivery

- Cadastro de endereços;
- área de entrega;
- Taxa de entrega;
- Status da entrega;
- Cadastro de entregadores;
- Pedidos para entrega;
- Acompanhamento do pedido;
- Integração com pagamentos online;

**Resultado:** Sistema expandido para delivery

## 10. Fase 10 - Aplicativo Mobile

- Definir tecnologia mobile;
- Reutilizar a API existente;
- Implementar autenticação;
- Criar telas principais;
- Implementar comandas;
- Implementar pedidos;
- Implementar notificações;
- Testar em Android;
- Testar em IOS;
- Publicas aplicativo;

**Resultado:** Aplicativo mobile integrado