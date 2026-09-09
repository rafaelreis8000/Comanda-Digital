# Usuários

Essa pasta contém a esquematização das classes de usuário do sistema

## Classes

### Usuário
 
 Representa de forma geral todo usuário do sistema. Reúnde dados para cadastro

 | Usuário |
 |---|
 | Nome |
 | CPF |
 | Telefone |

 Seus atributos são privados para garantir segurança no sistema

 ### Cliente

 Herda os atributos da classe Usuário, mas também possui características próprias, como pedido

 ### Funcionário

 Também herda de Usuário, mas com atributos adicionais de função