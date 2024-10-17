#Discreta 
## Definição:

	Dado um conjunto A, uma função de permutação de um conjunto A, ou uma permutação de A, é uma função bijetora de A para A, f:A -> A. Ou seja, como a função é bijetora, não há perda de elementos, pois os dois conjuntos possuem a mesma quantidade de elementos, dessa forma, nós apenas mudamos a posição dos elementos pertencentes ao conjunto A. Algo interessante de se notar, é que a função identidade de A apresenta as características de uma função de permutação (trivial), pois ele não altera nada no conjunto de partida.
	Dentro do mesmo contexto do conjunto A, o conjunto SA é o conjunto formado por todas as permutações de A, isto é, SA = {f: f:A --> A é bijetora}. Exemplo:

![[Funções de Permutação.png]]

	Observações: Se F é uma função que pertence ao conjunto SA, então a inversa dessa função também pertence a esse conjunto, ou seja, ela também é uma permutação. Além disso, se f e g pertencem ao conjunto SA, então a composta de f e g também pertence a esse conjunto, assim, ela é uma função de permutação.

## Representações de Funções de Permutação:

### Arranjo:
	As funções de permutação representam arranjos ordenados de objetos no domínio.
	Dessa forma, nós podemos representar F em forma de arranjo retangular, listando os elementos do domínio em uma linha e os elementos da imagem diretamente abaixo de seus antecedentes.

![[Permutação Arranjo retangular.png]]

### Notação em ciclo:

	Também podemos usar a notação de ciclo para representar as funções de permutação.
	O formato dessa notação é f = (a, b, c), em que:
* 1° - F leva cada elemento no que está a sua direita
* 2° - O último elemento da lista vai ser levado para o primeiro elemento da lista, ou seja, quando você chegar no elemento do início, você deve quebrar o ciclo e só será possível representar esse ciclo completamente por meio de composições.
* 3° - Os elementos do domínio que não aparecem no ciclo vão em si mesmos.

![[Notação em Ciclo.png]]

	Lembrando que você consegue fazer alterações cíclicas nesse ciclo sem alterar a permutação que é produzida por esse ciclo, ou seja, os elementos continuarão se relacionando com os mesmos elementos. Outra dica, a convenção é que você comece o ciclo pelo primeiro elemento do domínio para que, assim, você não se perca.
	A ação de GoF em qualquer elemento de A é determinado aplicando-se primeiro a função F e depois a função G. Se F e G são ciclos, então GoF também será calculado da mesma maneira.

#### Ciclos Disjuntos:
	Dados f, g pertencentes a SA, dizemos que f e g são ciclos disjuntos se a representação em ciclos destes não têm elementos em comum.
	
![[Ciclos Disjuntos.png]]

##### Observação:
* Se f, g pertencentes ao conjunto SA e F e G são ciclos disjuntos, então FoG = GoF, ou seja, f e g podem comutar.
* Se permutarmos ciclicamente os elementos de um ciclo qualquer e/ou se reordenarmos os ciclos que as compõem isto não mudará a permutação representada.
* Dessa forma, a menos destas possíveis variações, a representação por ciclos disjuntos é unica.



## Considerações Finais:

![[Ciclos considerações.png]]

![[Considerações Finais 2.png]]


### Desarrumação Total:

		Uma permutação de um conjunto que não leva nenhum elemento em si mesmo é chamado de desarrumação total. Os elementos de SA que não são desarrumações totais, se escritos como ciclo ou uma composição de ciclos disjuntos, terão pelo menos um elemento de A que não aparece.

### Permutações Especiais:

![[Permutações Especiais.png]]

![[Permutas Especiais 2.png]]

![[Permutas Especiais 3.png]]
