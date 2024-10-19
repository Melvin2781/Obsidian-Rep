#Discreta 
## Definição:

Dado um conjunto A, uma função de permutação de um conjunto A, ou uma permutação de A, é uma função bijetora de A para A, f:A --> A. Ou seja, como a função é bijetora, não há <mark style="background: #FFB86CA6;">perda de elementos</mark>, pois os dois conjuntos possuem a mesma quantidade de elementos, dessa forma, nós apenas <mark style="background: #FFF3A3A6;">mudamos a posição</mark> dos elementos pertencentes ao conjunto A. Algo interessante de se notar, é que a função identidade de A apresenta as características de uma função de permutação (trivial), <mark style="background: #FF5582A6;">pois ele não altera nada no conjunto de partida</mark>.

Dentro do mesmo contexto do conjunto A, o conjunto SA é o conjunto formado por todas as permutações de A, isto é, SA = {f: f:A --> A é bijetora}. Exemplo:

![[Funções de Permutação.png]]

Observações: Se F é uma função que pertence ao conjunto SA, então a <mark style="background: #FFB8EBA6;">inversa</mark> dessa função também pertence a esse conjunto, ou seja, ela também é uma permutação. Além disso, se f e g pertencem ao conjunto SA, então a <mark style="background: #FFB8EBA6;">composta</mark> de f e g também pertence a esse conjunto, assim, ela é uma função de permutação.

## Representações de Funções de Permutação:

### Arranjo:
As funções de permutação representam <mark style="background: #BBFABBA6;">arranjos ordenados</mark> de objetos no domínio.

Dessa forma, nós podemos representar F em forma de arranjo retangular, listando os elementos do <mark style="background: #FFB86CA6;">domínio em uma linha</mark> e os <mark style="background: #FFB86CA6;">elementos da imagem diretamente abaixo</mark> de seus antecedentes.

![[Permutação Arranjo retangular.png]]

### Notação em ciclo:

Também podemos usar a notação de ciclo para representar as funções de permutação.

```ad-note
title: Informações - Ciclo
collapse: open

O formato dessa notação é f = (a, b, c), em que:

* 1° - F leva cada elemento para o que está a sua direita.
* 2° - O último elemento da lista vai ser levado para o primeiro elemento da lista, ou seja, quando você chegar no elemento do início, você deve quebrar o ciclo e só será possível representar esse ciclo completamente por meio de composições.
* 3° - Os elementos do domínio que não aparecem no ciclo vão em si mesmos, pontos fixos.
```

![[Notação em Ciclo.png]]

Lembrando que você consegue fazer <mark style="background: #FFB8EBA6;">alterações cíclicas</mark> nesse ciclo sem alterar a permutação que é produzida por esse ciclo, ou seja, os elementos continuarão se relacionando com os mesmos elementos. Outra dica, a<mark style="background: #FFB8EBA6;"> convenção é que você comece o ciclo pelo primeiro elemento do domínio</mark> para que, assim, você não se perca.

A ação de GoF em qualquer elemento de A é determinado aplicando-se <mark style="background: #FFB86CA6;">primeiro a função F e depois a função G</mark>. Se F e G são ciclos, então GoF também será calculado da mesma maneira.

#### Ciclos Disjuntos:
Dados f e g pertencentes a SA, dizemos que f e g são ciclos disjuntos se a representação em ciclos destes <mark style="background: #FF5582A6;">não têm elementos em comum</mark>.
	
![[Ciclos Disjuntos.png]]
```ad-warning
title: Observação
collapse: open

* Se f e g pertencentes ao conjunto SA e F e G são ciclos disjuntos, então FoG = GoF, ou seja, f e g podem comutar.
* Se permutarmos ciclicamente os elementos de um ciclo qualquer e/ou se reordenarmos os ciclos que as compõem isto não mudará a permutação representada.
* Dessa forma, a menos destas possíveis variações, a representação por ciclos disjuntos é unica.
```

## Considerações Finais:

![[Ciclos considerações.png]]

![[Considerações Finais 2.png]]


### Desarrumação Total:

Uma permutação de um conjunto que <mark style="background: #FF5582A6;">não leva nenhum elemento em si mesmo</mark> é chamado de desarrumação total, pois <mark style="background: #ADCCFFA6;">não existem pontos fixos</mark>. Os elementos de SA que não são desarrumações totais, se escritos como ciclo ou uma composição de ciclos disjuntos, <mark style="background: #FFF3A3A6;">terão pelo menos um elemento de A que não aparece</mark>.

### Permutações Especiais:

![[Permutações Especiais.png]]

![[Permutas Especiais 2.png]]

![[Permutas Especiais 3.png]]
