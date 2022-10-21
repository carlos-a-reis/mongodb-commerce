# MongoDB Commerce

## Contexto

Este repositório se trata de uma série de aquivos Javascript com queries para resolver desafios propostos pela [Trybe](https://www.betrybe.com/) de consulta, inserção, atualização e deleção de dados em um banco de dados MongoDB chamado “commerce” que contem informações de lanches do McDonald's em uma coleção chamada “produtos”.

Este banco de dados possui informações como, nome, ingredientes, valores nutricionais e quantidade de vendas e curtidas de alguns produtos.

Seguem abaixo a descrição da funcionalidade de cada query em cada arquivo de desafio (indo do 1 ao 32) presente na pasta challenges deste repositório:

## Funcionalidade de Cada Desafio.

<details>
	<summary>
		<h4>Desafio 1</h4>
	</summary><br>

	Retorna a quantidade de documentos inseridos na coleção produtos.

</details>

<details>
	<summary>
		<h4>Desafio 2</h4>
	</summary><br>

	Ordena a coleção produtos pela quantidade de lanches vendidos em ordem crescente, mostrando apenas o nome e a quantidade de lanches vendidos.

</details>

<details>
	<summary>
		<h4>Desafio 3</h4>
	</summary><br>

	Retorna o lanche mais vendido, mostrando apenas o nome e a quantidade do lanche mais vendido.

</details>

<details>
	<summary>
		<h4>Desafio 4</h4>
	</summary><br>

	Retorna os lanches que tiveram vendas maiores que 50 e menores que 100, mostrando apenas o nome e a quantidade de lanches vendidos em ordem crescente.

</details>

<details>
	<summary>
		<h4>Desafio 5</h4>
	</summary><br>

	Retorna o nome, as curtidas e vendidos dos lanches que tiveram quantidade de curtidas igual a 36 ou tenham a quantidade de vendas igual a 85.

</details>

<details>
	<summary>
		<h4>Desafio 6</h4>
	</summary><br>

	Retorna o nome e as curtidas dos lanches que tiveram curtidas maiores que 10 e menores que 100.

</details>

<details>
	<summary>
		<h4>Desafio 7</h4>
	</summary><br>

	Retorna o nome e vendidos dos lanches que tenham sido vendidos com uma quantidade diferente de 50 e em que o campo tags não exista.

</details>

<details>
	<summary>
		<h4>Desafio 8</h4>
	</summary><br>

	Deleta os lanches com menos de 50 curtidas e retorna o nome dos lanches que restaram no banco.

</details>

<details>
	<summary>
		<h4>Desafio 9</h4>
	</summary><br>

	Retorna o nome de todos os lanches que possuam calorias abaixo de 500.

</details>

<details>
	<summary>
		<h4>Desafio 10</h4>
	</summary><br>

	Retorna o nome de todos os lanches que tenham o percentual de proteínas maior ou igual a 30 e menor ou igual a 40.

</details>

<details>
	<summary>
		<h4>Desafio 11</h4>
	</summary><br>

	Retorna o nome do produto, a quantidade de curtidas e quantos itens foram vendidos dos produtos que não sejam iguais a Big Mac e McChicken.

</details>

<details>
	<summary>
		<h4>Desafio 12</h4>
	</summary><br>

	Adiciona ketchup aos ingredientes para todos os sanduíches menos o McChicken, garantindo que não haja duplicidade nos ingredientes.

</details>

<details>
	<summary>
		<h4>Desafio 13</h4>
	</summary><br>

	Inclue o campo criadoPor em todos os documentos, colocando Ronald McDonald no valor desse campo.

</details>

<details>
	<summary>
		<h4>Desafio 14</h4>
	</summary><br>

	Retorna todos os lanches que possuem picles em seus ingredientes e mostra apenas os 3 primeiros itens contidos no array valoresNutricionais.

</details>

<details>
	<summary>
		<h4>Desafio 15</h4>
	</summary><br>

	Adiciona o campo avaliacao em todos os documentos da coleção e efetua alterações nesse campo.

</details>

<details>
	<summary>
		<h4>Desafio 16</h4>
	</summary><br>

	Adiciona o campo ultimaModificacao com a data corrente somente no sanduíche Big Mac.

</details>

<details>
	<summary>
		<h4>Desafio 17</h4>
	</summary><br>

	Retorna a quantidade total de produtos em uma nova coleção chamada resumoProdutos.

</details>

<details>
	<summary>
		<h4>Desafio 18</h4>
	</summary><br>

	Inclue bacon no final da lista de ingredientes dos sanduíches Big Mac e Quarteirão com Queijo.

</details>

<details>
	<summary>
		<h4>Desafio 19</h4>
	</summary><br>

	Remove o item cebola de todos os sanduíches.

</details>

<details>
	<summary>
		<h4>Desafio 20</h4>
	</summary><br>

	Remove o primeiro ingrediente do sanduíche Quarteirão com Queijo.

</details>

<details>
	<summary>
		<h4>Desafio 21</h4>
	</summary><br>

	Remove o último ingrediente do sanduíche Cheddar McMelt.

</details>

<details>
	<summary>
		<h4>Desafio 22</h4>
	</summary><br>

	Adiciona a quantidade de vendas dos sanduíches por dia da semana.

</details>

<details>
	<summary>
		<h4>Desafio 23</h4>
	</summary><br>

	Inseri os valores combo e tasty no array tags de todos os sanduíches e ordena os valores em ordem alfabética ascendente (A a Z).

</details>

<details>
	<summary>
		<h4>Desafio 24</h4>
	</summary><br>

	Ordena em todos os documentos os valores do array valoresNutricionais pelo campo percentual de forma decrescente.

</details>

<details>
	<summary>
		<h4>Desafio 25</h4>
	</summary><br>

	Adiciona o valor muito sódio ao final do array tags nos produtos em que o percentual de sódio seja maior ou igual a 40.

</details>

<details>
	<summary>
		<h4>Desafio 26</h4>
	</summary><br>

	Adiciona o valor contém sódio ao final do array tags nos produtos em que o percentual de sódio seja maior do que 20 e menor do que 40.

</details>

<details>
	<summary>
		<h4>Desafio 27</h4>
	</summary><br>

	Conta quantos produtos contém Mc no nome, sem considerar letras maiúsculas ou minúsculas.

</details>

<details>
	<summary>
		<h4>Desafio 28</h4>
	</summary><br>

	Conta quantos produtos têm 4 ingredientes.

</details>

<details>
	<summary>
		<h4>Desafio 29</h4>
	</summary><br>

	Renomeia o campo descricao para descricaoSite em todos os documentos.

</details>

<details>
	<summary>
		<h4>Desafio 30</h4>
	</summary><br>

	Remove o campo curtidas do item Big Mac.

</details>

<details>
	<summary>
		<h4>Desafio 31</h4>
	</summary><br>

	Retorna o nome dos sanduíches em que o número de curtidas é maior que o número de sanduíches vendidos.

</details>

<details>
	<summary>
		<h4>Desafio 32</h4>
	</summary><br>

	Retorna o nome e a quantidade de vendas (vendidos) dos sanduíches em que o número de vendas é múltiplo de 5.

</details>
