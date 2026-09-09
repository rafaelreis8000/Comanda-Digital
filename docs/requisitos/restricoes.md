# Restrições do Projeto

## 1. Tecnologias

- Backend: Java + Spring Boot;
- Frontend: React + TypeScript;
- Banco de Dados: PostgreDWL;
- API: REST;
- Aplicativo futuro: Flutter;

## 2. Estrutura

O projeto deverá seguir a estrutura:

- Controller;
- Service;
- Repository;
- Banco de Dados;

As regras de negócio devem operar principalmente na camada Service

## 3. Funcionalidades Iniciais

- Cadastro de Usuários;
- Cadastro de Clientes;
- Cadastro de categorias;
- Cadastro de produtos;
- Cadastro de mesas;
- Criação de pedidos;
- Controle dos itens dos pedidos;
- Controle do status dos pedidos;
- Registro de pagamentos;

## 4. Usuários

Deverão existir diferentes níveis de acesso:

- Dono;
- Funcionário;
- Cliente;

Cada tipo de usuário terá níveis de acesso e permissões diferentes

## 5. Pedidos

Os pedidos deverão possuir status:

| Status |
|---|
| ABERTO |
| PREPARANDO |
| PRONTO |
| ENTREGUE |
| FECHADO |
| CANCELADO |

Alterações que colocam os pedidos em estado inválido devem ser proibidas

## 6. Pagamentos

Inicialmente serão consideradas as formas:

- Pix;
- Cartão de Crédito;
- Cartão de Débito;
- Vale-Alimentação;

## 7. Segurança

- As senhas não poderão ser armazenadas em texto puro;
- O acesso deverá possuir autenticação;
- Cada usuário deverá acessar somente as funcionalidades permitidas;

## 8. Interface

- Web;

## 9. Funcionalidades futuras

- Versão Mobile;
- Versão Desktop;
- Delivery;
- Impressão de pedidos;
- WebSocket;
- Relatórios;
- Gráficos;
- Inteligência Artificial;