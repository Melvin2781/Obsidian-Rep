#Discreta 

## Definição: 
### Definição Informal:
	Uma função é uma "Regra" ou 'Mecanismo' que transforma uma grandeza/quantidade em outra.
### Definição Formal:
	Uma relação F é chamada de função desde que (a,b) em F e (a,c) em F implique que a = c. Ou seja, um antecedente só pode possuir/gerar uma única imagem. Algo a se observar é que geralmente usamos uma notação diferente dos pares ordenados para representar funções. (1,2) <---> F(1) = 2.

## Classificação:

### Função Injetora:
	Uma função é injetora, ou injetiva, ou um para um, se sempre que (x, b) e (y, b) pertencem à função, x = y, ou seja, as imagens da função terão um único antecedente, assim, evitando a ambiguidade de valores. Em outras palavras, se x for diferente de y, então f(x) vai ser diferente de f(y), ou de forma equivalente, se f(x) = f(y), então x = y. 
	Para provarmos que uma função não é injetora, devemos apresentar um contraexemplo.
	A partir desse conhecimento, nós podemos afirmar que: F^-1 é uma função, se, e somente se, a função F for injetora
	Por fim, nós utilizaremos essa informação sobre as funções injetoras para conseguir transformar as relações inversas em funções, dessa forma, só resta igualar o domínio de F^-1 ao conjunto B.

### Função Sobrejetora:
	Uma função é sobrejetora, se para todo b pertencente ao conjunto B, existe um a pertencente ao conjunto A, tal que f(a) = b, ou seja, como todos os elementos do conjunto B possuem um antecedente em A, então B = Im(F). Assim, resolvendo o problema do domínio da função inversa.

### Função Bijetora:
	Uma função:A -> B é bijetora quando ela é tanto sobrejetora quanto injetora, ou seja, as imagens só possuem um único antecedente e para todo b pertencente ao conjunto B, existe um a pertencente ao conjunto A, tal que f(a) = b, com isso, Im(F) = B.
	Algo importante de se comentar é o fato de que uma função só possuirá uma função inversa se ela for bijetora.



## Igualdade de funções:

	Algo imporante de se notar na igualdade de funções é que: duas funções só são iguais quando elas possuem a mesma propriedade de formação e elas possuem o mesmo domínio. Isso ocorre pelo fato de que quando nós temos um domínio diferente em uma função, nós podemos ter pares ordenados diferentes que pertencem a essa função, ou seja, elas se tornam funções/relações diferentes.


## Composição de Funções:

	Sejam os conjuntos A, B e C e sejam f : A -> B e g: B -> C. Então, a função g o f é uma função de A para C, definida por (g o f)(a) = g(f(a)). Se lembre de quem fica mais à direita na função composta, é o elemento que se relaciona primeiro com o objeto (a).
		Coisas interessantes de se notar sobre a função composta é que: o domínio dessa função é o domínio da função mais interna e a imagem da função composta está contida na imagem da função mais externa. Outra coisa é que a função composta não é comutativa.
	Outra curiosidade sobre as funções compostas é que elas possuem associatividade, ou seja, você pode mudar a posição dos parênteses. Assim, h o (g o f) = (h o g) o f.

### Função Identidade:

	Seja A um conjunto, a função identidade em A é a função idA, cujo domínio é A e imagem é A e para todo a pertencente ao conjunto A, idA(a) = a. Ou seja, idA = {(a,a) tal que a pertence a A}. Nós podemos obter uma função identidade por meio da composição de funções, onde a função mais próxima da variável em composição com sua inversa faz uma função identidade do seu domínio.
	Uma curiosidade é que a composta de f o idA = idB o f = f;
	
![[Função-Identidade.png]]



## Contagem de Funções:

	A contagem de funções é uma maneira de conseguirmos identificar de quantas maneiras nós podemos formar funções de um conjunto para outro, podendo ser funções gerais/injetivas/sobrejetivas/bijetivas.
	Ao todo, nós podemos fazer b^a funções --> f:A --> B com o conjunto A e B, de modo que, b = |B| e a = |A|. A notação para todas essas funções é o conjunto B^A que representa o conjunto de todas as funções f:A -> B.
	Quantas funções injetoras nós podemos formar a partir de um conjunto A e um conjunto B? Lembrando que não podemos ter uma função injetora em que temos |A| > |B|, pois assim nós teriamos elementos de B que possuiriam mais de um antecedente, assim, rompendo com a injetividade. Nós podemos transformar essa afirmação por contraposição também.
	Para responder a questão anterior, nós podemos pensar na ideia de que vamos multiplicar as possibilidades a partir de b * (b-1) * (b-2) * ... * (b-(a-1)). Ou seja, fazendo uma manipulação álgebrica para deixarmos no formato de Fatorial: temos a b!/(b-a)! escolhas.
	
	Quantas funções sobrejetoras nós podemos formar a partir de um conjunto A e um conjunto B? Recordando que não podemos formar uma função sobrejetora em que |B| > |A|, pois assim nem todos os elementos de B teriam um antecedente em A, ou seja, não formaria uma função sobrejetora. Nós podemos transformar essa afirmação por contraposição também.

	Neste caso, nós podemos utilizar o problema de contas de lista: Imagine que nós temos que escolher elementos de um conjunto com n objetos para compor uma lista de k espaços, assim, teríamos n^k possibilidades de fazer isto. Nós vamos pegar esse total de listas e subtrair das listas que nós não queremos para que, assim, conseguirmos chegar à lista que nós queremos.

![[SobrejetoraContagem.png]]

	Quantas funções bijetoras podem ser obtidas a partir de um conjunto A e um conjunto B? Podemos afirmar que |A| = |B|. Se a = b, o número de funções sobrejetoras é a!.
## Extra:
### Formas de representação de funções:

#### - Gráficos:
	Gráficos geralmente são utilizados em funções que possuem um conjunto contínuo, ou seja, o conjunto dos reais, que tem uma infinitude de elementos entre um elemento e outro. Mas, quando nós falamos de matemática discreta, isso não se torna tão interessante, visto que, nós ou utilizamos conjuntos, ou o conjuntos dos Naturais ou o conjunto dos Inteiros. 
	Assim, a representação por gráficos nesses contextos não fornece uma visão decente do panorama da função.

#### - Diagrama de Venn:
	Principal método utilizado para representar as funções em conjuntos discretos(finitos).


### Tópicos relevantes:
- Nota relevante para a leitura do tópico: [[Relações]], [[Função Inversa]].

