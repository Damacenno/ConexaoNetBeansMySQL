# ConexaoNetBeansMySQL
Esta classe serve para realizar a conexão de um programa Java com um banco de dados local para apurações.

Para que essa conexão aconteça, utiliza-se do servidor Apache e MySQL do XAMPP V3.3.0.
Também utiliza da biblioteca JDBC Para MySQL, instalada diretamente dentro da IDE que
foi utilizada.


O link de conexão é - > (jdbc:mysql://127.0.0.1:3306/java","root","")

Onde "root" é o o usuário de conexão no banco de dados e as aspas em branco é a senha.

=======================================================================

Possível erro - > É capaz que, dependendo da configuração da sua máquina, ao rodar seu
programa a IDE acuse erro de conexão, declarando que o link de comunicação foi inváli-
do. Caso isso aconteça, experimente trocar a porta presente no link de conexão do JDBC
para 3307.

Obs: Não sei explicar ao certo o porque disso, o que posso afirmar é que isso tem a ver
com a porta de conexão com a internet da máquina.

