## Banco de Dados

-   Modelo conceitual: Criar a entidade e atributos
-   Modelo Lógico: Aonde a entidade vira uma tabela e os atributos colunas. Para bancos de dados orientados a objetos, se usa classe.
-   Modelo físico: Escrever a tabela com os comando SQL
-   DBA gera o script do banco quando recebe o modelo lógico
-   1° Forma Normal: Uma relação está na 1° FN se e somente se todos os seus atributos contêm apenas valores atômicos (simples, indivisíveis)
-   2° Forma Normal: Uma relação encontra-se na 2FN se e somente se estiver na 1° Forma Normal e não contém depencdências parciais (Uma coluna depende apenas 
	de uma parte de uma chave primária composta)
-   3° Forma Normal: Uma relação está na 3° Forma Normal se e somente se estiver na 2° Forma Normal e nenhum atributo não primo (isto é, que não seja membro 
	de uma chave) for transistivamente dependente da chave primária (quando uma coluna, além de depender da chave primária de uma tabela, depende de outra 
	coluna ou conjunto de colunas da tabela)
-   DDL: Criação e alteração de tabelas
-   DDL: Manipulação de dados (insert, update, delete, select)
-	Existe duas formas de relacionar duas tableas quando o relacionamento for 1:1
        -   Quando a segunda tabela possuir PK e FK do campos igual a primeira tabela
        -   Quando a segunda tabela possuir um UNIQUE na FK (A FK nesse caso não precisa ser PK)
-	Links de referência
        -   https://sites.google.com/site/uniplibancodedados1/aulas/aula-7---tipos-de-relacionamento
        -   https://www.tech-recipes.com/rx/56738/one-to-one-one-to-many-table-relationships-in-sql-server/