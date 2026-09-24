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
| RF14 | Usuários | Cadastrar usuários e controlar seus perfis e permissões. |
| RF15 | Autenticação | Permitir login e controle de acesso ao sistema. |
| RF16 | Auditoria | Registrar operações relevantes realizadas pelos usuários. |
| RF17 | Expansão | Manter a arquitetura preparada para futuras funcionalidades, como delivery e estoque. |

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

### RF03 - Produtos

**Definition of Ready**
- Os atributos forem definidos;
- Os campos obrigatórios forem definidos;
- Os relacionamentos forem definidos;

**Definition of Done**
- É possível cadastrar produtos;
- É possível gerenciar produtos;
- Produtos possuem categorias;
- Produtos indisponíveis ficam inativos;
- Produtos indisponíveis não ficam visíveis;

### RF04 - Cardápio

**Definition of Ready**
- Categorias e produtos devem estar definidos;
- As informações que serão exibidas acerca do produto definidas;
- O comportamento de categorias inativas e sem produtos deve ser levantado;

**Definition of Done**
- O cardápio exibe os produtos disponíveis;
- É possível visualizar o cardápio;
- Produtos podem ser selecionados apra um pedido;

### RF05 - Mesa

**Definition of Ready**
- Os dados de uma mesa forem definidos;
- A relação entre mesa e comanda for definida;
- O corpotamento de mesas disponíveis e ocupadas forem definidos;

**Definition of Done**
- O status da mesa pode ser consultado;
- Uma mesa pode ser marcada para uma comanda;
- O status e o número de uma mesa pode ser modificado;

### RF06 - Comandas

**Definition of Ready**
- Os dados da comanda forem definidos;
- Os campos obrigatórios de uma comanda foram definidos;
- A relação entre comanda e mesa forem definidas;
- As condições de abertura e fechamento foram definidas;

**Definition of Done**
- Uma comanda pode ser aberta;
- Uma mesa pode ser associada;
- Um cliente deve ser assimilado;
- O status pode ser alterado;

### RF07 - Pedidos

**Definition of Ready**
- A estrutura de pedidos for definida;
- A relação entre pedido, comanda e itens for definida;
- As definições e status de um pedido forem definidas;

**Definition of Done**
- O pedido fica associado à comanda;
- É possível fazer um pedido;
- O pedido pode ser alterado;
- O pedido evolui para "em preparo" e "entregue";

### RF08 - Itens

**Definition of Ready**
- Quantidade mínima e máxima foram definidas;
- Os campos de um item foram definidos;
- Os campos obrigatórios foram elaborados;
- Definir seu relacionamento com um produto;

**Definition of Done**
- Um pedido pode ser adicionado a um item;
- Sua quantidade pode ser escolhida;
- Observações podem ser apontadas;

### RF09 - Status

**Definition of Ready**
- Todos os status necessários foram definidos;
- O relacionamento com a comanda foi definido;

**Definition of Done**
- Todo pedido possui status;
- O status se altera conforme o pedido evolui;

### RF10 - Cancelamento

**Definition of Ready**
**Definition of Done**

### RF11 - Total

**Definition of Ready**
**Definition of Done**

### RF12 - Pagamento

**Definition of Ready**
**Definition of Done**

### RF13 - Histórico

**Definition of Ready**
**Definition of Done**

### RF14 - Usuários

**Definition of Ready**
**Definition of Done**

### RF15 - Autenticação

**Definition of Ready**
**Definition of Done**

### RF16 - Auditoria

**Definition of Ready**
**Definition of Done**

### RF17 - Expansão

**Definition of Ready**
**Definition of Done**



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