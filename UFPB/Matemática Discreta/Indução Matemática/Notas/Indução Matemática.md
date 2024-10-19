---
Assunto: Indução Matemática
Dependências: "[[Ordem Parcial - Total]]"
---
#Discreta 

## Definição:

### Definição Informal:

Nós podemos utilizar o <mark style="background: #D2B3FFA6;">efeito cascata em uma fila de peças de dominó</mark> para exemplificar a indução matemática, em que, quando o primeiro dominó cai, as peças mais próximas começam a <mark style="background: #FF5582A6;">cair uma após a outra</mark>.

### Definição Formal:

Nesse contexto, podemos expressar esse fenômeno informal em uma linguagem mais formal ou seja, iremos apresentar uma <mark style="background: #FF5582A6;">definição que utiliza a linguagem matemática a partir de duas propriedades</mark>:

* a) a primeira peça é derrubada em direção às outras peças.
* b) Caso alguma peça esteja próxima o suficiente da sua vizinha consecutiva, então, ao ser derrubada, fará com que a sua <mark style="background: #FFB8EBA6;">vizinha consecutiva também seja derrubada</mark>.

## Princípios da Indução:

```ad-important
title: Importante
collapse: open

* A prova por Indução pode ser chamada de Princípio de Indução Matemática ou Princípio da Indução Finita.
* Essa prova por Indução será divida em duas formas, a indução fraca e a indução forte, existindo uma equivalência entre essas duas.
* É uma técnica utilizada para lidar com tipos de dados que pertencem a conjuntos bem-ordenados.
* Dada uma relação de boa-ordem, pode-se aplicar indução para provar propriedades que valem para todos os elementos de um tipo de dado.
* Para facilitar a vida dos alunos, em matemática discreta, utilizaremos apenas o conjunto dos números naturais e a relação de menor igual.
```
## Teorema utilizado na indução:


![[Demonstração Indução.png]]
![[Demonstração Indução 2.png]]

## Roteiro da Prova por Indução Fraca:

Para provar que uma <mark style="background: #FFB86CA6;">propriedade é verdadeira</mark> para todos os n's pertencentes ao conjunto dos naturais, nós precisamos seguir um certo <mark style="background: #FF5582A6;">roteiro</mark> para que, assim, fique mais fácil de organizar essas demonstrações.
Algo importante de se salientar é que teremos que realizar várias manipulações algébricas para chegarmos aos resultados desejados durante uma demonstração por indução.

Nesse caso, nós utilizaremos as duas demonstrações anteriores como base para as demonstrações por indução. Principalmente o princípio fraco da indução matemática:

```ad-abstract
title: Passo a Passo
* 1. Etapa Básica: Você precisa provar que P(1) é verdadeira. - Nunca se esqueça de realizar esse passo, pois ele é extremamente importante para decidir se você continuará ou não na indução.
* 2. Etapa Indutiva Você precisa provar que: 
	* 2.0 Se P(h) é verdadeira, então P(h+1) também é verdadeira, mais precisamente:
	* 2.1 Hipótese da Indução: Suponha que o resultado é verdadeiro para n = h.
	* 2.2 Tese: Usando a hipótese da indução, prove que o resultado é verdadeiro para n  = h + 1.
 * 3 Etapa Geral: Portanto, o resultado será verdadeiro para todos os números naturais, ou seja, P(n) é verdadeiro para todo n pertencente ao conjunto dos números naturais. Isso ocorre devido ao princípio fraco da indução.
```
### Variante da Prova por Indução Fraca:

Existe uma variante de prova por indução normal, em que nós utilizamos um elemento <mark style="background: #FFB86CA6;">diferente do 1</mark> como o primeiro elemento da relação que ocorre no conjunto, nesse caso esse número seria o n0. Ou seja, nós realizaremos o mesmo roteiro da Indução Fraca, com a diferença que <mark style="background: #FF5582A6;">começaremos provando a propriedade para o primeiro elemento do conjunto escolhido</mark>, assim, não necessariamente teremos que trabalhar com os naturais.

Uma outra diferença, é que não pegaremos todos os naturais igual foi feito anteriormente, <mark style="background: #FFB8EBA6;">nesse caso nós iremos pegar todos os elementos que são maiores ou iguais ao elemento inicial</mark>.

## Prova por Indução Forte:

Em algumas ocasiões, nós podemos não ter as <mark style="background: #FF5582A6;">informações necessárias</mark> para demonstrar algo pelo método da Indução Fraca, por esse motivo, poderemos utilizar o método de demonstração por Indução Forte, uma maneira uma pouco mais parruda de provar as coisas.
	
![[Falha-indFraca.png]]

Mesmo assim, o roteiro da indução forte é bem semelhante ao roteiro da variante da indução fraca, com a diferença que vamos utilizar um <mark style="background: #FFB86CA6;">k para representar os elementos que cumprem com a proposição exposta</mark>. Ou seja, para todo n > n0, a validez de p(k), para qualquer n0 <= k <= n, implica na validez de p(n+1), assim, nós podemos utilizar os <mark style="background: #FF5582A6;">elementos anteriores ao n</mark> para provar a propriedade para o elemento n+1. Esse método de indução forte representa o efeito cascata de um jeito mais fidedigno, pois para uma propriedade chegar ao elemento n, <mark style="background: #FFB86CA6;">ela deve ter passado por todos os elementos antes dela</mark>.

Lembrando que a indução forte e a indução fraca são equivalentes, dessa forma, você consegue provar as proposições com qualquer uma das duas, mas, a indução forte continua sendo um método um pouco mais resistente para <mark style="background: #FFF3A3A6;">problemas que necessitam de mais informações</mark>. Muitas vezes sendo um método mais fácil de se realizar uma prova por indução.

![[Equivalencia-Inducao.png]]