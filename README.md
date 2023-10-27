
# Banco de Dados Distribuído
`Algumas informações sobre banco de dados distribuídos, além de um esboço sobre MongoDB.`

Criado para trabalho da cadeira de Banco de Dados II, do professor [Alex Souza](https://github.com/aasouzaconsult) @aasouzaconsult.

## Definição
Um banco de dados distribuído, é como um grande quebra-cabeça, onde os dados são as peças e os servidores são as mesas onde você monta o quebra-cabeça.

Em vez de termos um único quebra-cabeça em uma única mesa, temos várias mesas interconectadas em uma sala, cada uma com algumas peças do quebra-cabeça. Essas mesas (servidores) trabalham juntas para formar a imagem completa, gerando maior eficácia no trabalho e reduzindo o risco de falhas.

## Exemplos de bancos de dados distribuídos
Existem vários bancos de dados distribuídos no mercado. Dentre eles:

-   RDS AWS;
-   Azure SQL Database;
-   Cloud Bigtable;
-   MemSQL (ou SingleStore);
-   FoundationDB;
-   CockroachDB;
-   Cassandra Apache;
-   Apache HBase;
-   ScyllaDB;
-   MongoDB;
-   Oracle RAC;
-   Couchbase;
-   ArangoDB;
    
Hoje, vamos falar um pouco de MongoDB.

## MongoDB
O MongoDB é um tipo de banco de dados que trabalha com uma abordagem moderna. É um banco de dados NoSQL, ou seja, se diferencia dos bancos de dados relacionais tradicionais, pois é não relacional. Ele é flexível, escalável e se encaixa bem com aplicativos que precisam de estrutura de dados dinâmica, além de ser gratuito.

Apesar de “não nascer” como um banco de dados distribuído, ele pode ser adaptado para tal, ou seja, ele é escalável, permitindo replicação de dados para alta disponibilidade e tolerância a falhas.

### Vantagens
-   Sistema de Replicação:
	> Permite fazer cópias dos dados em vários servidores, de modo a trazer alta disponibilidade, e tolerância a falhas. uma vez, que, mesmo que um servidor pare, ainda haverá os demais para fornecer os dados.

-   Sistema de Sharding:
	> Também é possível dividir os dados (shards) em vários servidores, de modo a facilitar o trato com grande volume de dados.

-   Indexação:
	> Permite indexar campos em documentos tanto como primários, quanto como secundários, de modo a melhorar o desempenho de pesquisas no banco de dados, ou seja, permite que a pesquisa seja realizadas em índices, logo, muito mais rápida.

-   Balanceamento de carga:
	> De modo a reduzir a carga utilizada em cada servidor, o MongoDB trabalha com balanceamento de cargas, de modo a assegurar o uptime, bem como a consistência dos dados e o trabalho com aplicativos escaláveis.

Além de todas essas vantagens, o MongoDB também possui consultas ad-hoc, pode trabalhar como um sistema de armazenamento de arquivos, possui agregação e muito mais.
