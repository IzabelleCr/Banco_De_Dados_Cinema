## Banco De Dados Cinema



A proposta deste documento é apresentar, de maneira técnica, a modelagem para um sistema de gerenciamento de um cinema. Para isso, foi necessária a elaboração de um projeto de banco de dados através dos modelos conceitual e lógico e físico, para incorporar esses elementos e, mais tarde, levá-los às ferramentas de programação com o intuito de executar simulações físicas.


## Estrutura do Banco de Dados
#### Modelos de Dados
###### Modelo Conceitual
O modelo conceitual identifica os principais componentes do sistema de gerenciamento de cinema:
#### Entidades:
-	Filmes
-	Clientes
-	Sessões
-	Salas
-	Ingressos
-	Métodos de Pagamento
-	Funcionários
-	Vendas
-	Produtos
###### Relacionamentos:
-	Exibe (Filmes - Sessões)
-	Ocupa (Sessões - Salas)
-	Compra (Clientes - Ingressos)
-	Inclui (Sessões - Ingressos)
-	Realiza (Funcionários - Vendas)
-	Efetua (Ingressos - Métodos de Pagamento)
-	Contém (Vendas - Produtos)
###### Modelo Lógico
- O modelo lógico detalha as entidades e relacionamentos, transformando-os em tabelas e colunas para serem utilizadas no modelo físico.
###### Modelo Físico

O modelo físico foi implementado em SQL, com a criação das tabelas e definição das chaves primárias e estrangeiras.
