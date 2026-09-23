# Requisitos Funcionais

## 1. Objetivo
Este documento define todos os requisitos funcionais do sistema, elaborados buscando atender as necessidades do usuário durante sua operação.

## 2. Requisitos

| Código | Requisito | Descrição |
|---|---|---|
| RF01 | Clientes | Cadastrar, consultar, alterar e inativar clientes. |
| RF02 | Categorias | Cadastrar e gerenciar categorias do cardápio. |
| RF03 | Produtos | Cadastrar, alterar, consultar e inativar produtos. |
| RF04 | Cardápio | Exibir produtos disponíveis organizados por categoria. |
| RF05 | Mesas | Cadastrar e controlar o status das mesas. |
| RF06 | Comandas | Abrir, consultar e encerrar comandas vinculadas às mesas. |
| RF07 | Pedidos | Registrar, alterar, remover e consultar pedidos. |
| RF08 | Itens | Adicionar produtos, quantidades e observações aos pedidos. |
| RF09 | Status | Controlar o andamento dos pedidos. |
| RF10 | Cancelamento | Permitir o cancelamento de pedidos conforme as regras do sistema. |
| RF11 | Total | Calcular automaticamente o valor dos itens e da comanda. |
| RF12 | Pagamento | Registrar a forma de pagamento no fechamento da comanda. |
| RF13 | Histórico | Consultar comandas e pedidos já encerrados. |
| RF14 | Cozinha | Exibir pedidos e permitir a atualização de seus status. |
| RF15 | Usuários | Cadastrar usuários e controlar seus perfis e permissões. |
| RF16 | Autenticação | Permitir login e controle de acesso ao sistema. |
| RF17 | Auditoria | Registrar operações relevantes realizadas pelos usuários. |
| RF18 | Expansão | Manter a arquitetura preparada para futuras funcionalidades, como delivery e estoque. |

## 2.1 DOR e DOD

### RF01 - Clientes

**Definition of Ready**
- Definidos quais dados serão utilizados para cadastro;
- Definidos quais campos serão obrigatórios;
- Definida a Identificação única do cliente;

**Definition of Done**
- For possível cadastrar um cliente válido;
- O sistema impedir cadastros inválidos;
- Possibilitar consulta de clientes cadastrados;
- For possível inativar um cliente;
- A inativação não remover registros históricos do contato;
- CLientes inativos não possam interagir no sistema;

### RF02 - Categorias

**Definition of Ready**
- Os dados da categoria forem definidos;
- O nome e demais atributos necessários definidos;
- Definir relação entre categoria e produtos;
- Definir permissões de gerenciamento;

**Definition of Done**
- For possível cadastrar uma categoria;
- For possível consultar as categorias;
- For possível alterar as categorias;
- A categoria for utilizada para agrupar tipos de produto;
- Categorias inativas ficarem ocultas no cardápio;

## 3. Regras Gerais

- Produtos indisponíveis não podem ser adicionados em novos pedidos;
- Uma mesa ocupada possui uma comanda ativa;
- Pedidos cancelados não entram no cálculo da comanda;
- O valor dos pedidos deve ser calculado automaticamente;
- Comandas encerradas não podem receber novos pedidods;
- Registros históricos importantes não devem ser excluídos fisicamente;
- O acesso às funcionalidades deve respeitar as permissões do usuário;
- O sistema deverá permitir futuras expansões sem grandes alterações na estrutura principal;

## 4. Prioridades

### Alta
- Produtos e Categorias;
- Mesas;
- Comandas;
- Pedidos;
- Cálculos de valores;
- Fechamento;
- Usuários e autenticação;
- Cozinha;

### Média
- Clientes;
- Histórico;
- Auditoria;

### Baixa
- Delivery;
- Controle de Estoque;