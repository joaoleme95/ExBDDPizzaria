# Tabelas e Consultas de Pizza

Neste exemplo, criamos um conjunto de tabelas relacionadas a pizzarias, pizzaiolos, receitas e tipos de pizza. Em seguida, realizamos várias consultas para obter informações sobre os pizzaiolos, tipos de pizza, ingredientes e instruções de preparo. Aqui estão as principais consultas:

1. `SELECT B.NOME, A.DESCRICAO, A.SABOR` - Mostra todas as pizzas e os pizzaiolos aptos a produzi-las.

2. `SELECT INGREDIENTES, DESCRICAO` - Mostra todas as pizzas e seus ingredientes.

3. `SELECT A.INGREDIENTE, B.INSTRUCAO` - Mostra todos os ingredientes e as pizzas onde são utilizados.

4. `SELECT B.NOME, A.SABOR, C.INSTRUCAO` - Exibe os sabores de todas as pizzas, o nome dos pizzaiolos que as fazem e as instruções para produzi-las.

Cada consulta fornece informações específicas sobre as pizzas e os pizzaiolos, permitindo que você obtenha insights sobre o processo de preparo de pizzas.
