## Banco De Dados Cinema


###### Este projeto visa criar um sistema de gerenciamento de banco de dados para um cinema, permitindo o controle de clientes, funcionários, filmes, sessões, ingressos, vendas e métodos de pagamento. O desenvolvimento foi realizado em três etapas principais: modelagem conceitual, lógica e física, utilizando a linguagem SQL para a implementação do modelo físico.

## Estrutura do Banco de Dados
#### Modelos de Dados
###### Modelo Conceitual
O modelo conceitual identifica os principais componentes do sistema de gerenciamento de cinema:
-	Entidades:
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
