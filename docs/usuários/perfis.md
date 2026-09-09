# Perfis de Usuário

Foram definidos os seguintes perfis:

| Nome | Descrição |
|---|---|
| Administrador | Responsável pelo gerenciamento das informações e configurações administrativas |
| Funcionário | Responsável pelo atendimento, gerenciamento de mesas, comandas e pedidos. |
| Cliente | Pessoa cadastrada para identificação e associação às comandas. Não possui acesso às funções administrativas |

## 1. Administrador

Possui acesso a todas as funcionalidades do sistema, especialmente às administrativas

### Permissões

- Cadastrar funcionários;
- Alterar funcionários;
- Desativas funcionários;
- Definir permissões;
- Cadastrar clientes;
- Alterar clientes;
- Consultar clientes;
- Cadastrar produtos;
- Alterar produtos;
- Desativar produtos;
- Gerenciar categorias do cardápio;
- Cadastrar mesas;
- Alterar mesas;
- Desativar mesas;
- Consultar comandas;
- Consultar pedidos;
- Consultar pagamentos;
- Configurar informações do estabelecimento;
- Cadastrar e alterar formas de pagamento;

## 2.Funcionário

Perfil responsável pela operação do sistema

### Permissões

- Consultar mesas;
- Identificar mesas disponíveis e ocupadas;
- Abrir comanda;
- Associar comanda à mesa;
- Cadastrar cliente;
- Consultar cliente;
- Alterar dados do cliente;
- Consultar cardápio;
- Adicionar produtos às comandas;
- Alterar quantidade do produto;
- Remover itens da comanda;
- Adicionar observações;
- Enviar pedidos;
- Consultar pedidos;
- Consultar comanda;
- Fechar comanda;
- Consultar valor total;
- Selecionar forma de pagamento;
- Gerar qr code PIX;
- Finalizar comanda;

## 3. Cliente

No primeiro projeto não faz interação direta com a plataforma

### Permissões

- Identificação;
- Associação à comanda;
- Histórico de consumo;
- Identificação dos pedidos;