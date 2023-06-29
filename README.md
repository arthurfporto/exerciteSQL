# Exercite SQL
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/arthurfporto/exerciteSQL/HEAD)
<hr>
O objetivo desse repositório é propor atividades para que você possa exercitar os seus conhecimentos em SQL. 

Os exercícios foram construídos utilizando o <a href='https://jupyter.org/' target='_blank'>Jupyter notebook</a> em conjunto com o <a href='https://mybinder.org/' target='_blank'>Binder</a>. Aqui o que possibilita a utilização de SQL no Notebook é o <a href='https://www.sqlalchemy.org/' target='_blank'> SQLAlchemy </a>  adicionado através da <a href='https://github.com/catherinedevlin/ipython-sql' target='_blank'>ipython-sql</a>.

:thought_balloon: Deseja um tutorial para configuração do ambiente? <a href='https://www.datacamp.com/community/tutorials/sql-interface-within-jupyterlab' target='_blank'>Clique Aqui!</a>

## Como utilizar
Basta clicar em  [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/arthurfporto/exerciteSQL/HEAD)  e selecionar o notebook desejado.

Depois que você rodar o ambiente, indico abrir o Notebook <b>#00 - Tutorial</b> para entender como funciona o processo. 

### ElephantSQL
Para utilizar os bancos de dados com o Postgres, uma opção é o <a href='https://www.elephantsql.com/' target='_blank'> ElephantSQL :elephant: </a>

1. Faça o login no ElephantSQL
2. Criando um novo Banco de Dados
    - Clique em "Create New Instance"
    - Defina um nome
    - Clique em "Select Region", depois em "Review" e "Create Instance"
3. Inserindo informações
    - Selecione a instância criada
    - Selecione a opção "Browser" no menu lateral
    - Copie o código disponível em um dos arquivos ".txt" da pasta [databases](databases/) 
    - Cole o código na caixa "SQL Query" e Execute