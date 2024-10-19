#Discreta
## Definição: 
Uma relação entre A e B é um <mark style="background: #BBFABBA6;">subconjunto</mark> do produto cartesiano A X B. Ou seja, R é uma relação entre A e B, se, e somente se, R está contido no conjunto AXB.
	
## Símbolos para representar a relação:
Nós podemos utilizar a notação **aRb** para indicar que o par ordenado (a,b) pertence à relação. Lembrando que o par ordenado só pertence à relação se ele pertencer ao produto cartesiano AXB e se ele cumprir a proposição de R.
## Maneiras de representar as relações (Finitas):
### 1°. Diagrama de Venn
Nós podemos utilizar diagramas de Venn, semelhante à <mark style="background: #FF5582A6;">representação de funções finitas</mark>, mas, nesse caso, nós podemos enviar mais de uma seta do conjunto A(Conjunto que contém o domínio) para o conjunto B(Conjunto que contém o conjunto imagem).

### 2°. Gráfico cartesiano
Nesta representação em gráfico, a <mark style="background: #FFB86CA6;">abscissa é o primeiro conjunto</mark> do produto cartesiano e a <mark style="background: #ABF7F7A6;">ordenada é o segundo conjunto</mark> do produto cartesiano. Os elementos do produto cartesiano A X B, são os <mark style="background: #BBFABBA6;">vértices dos quadriláteros</mark> formados pelas retas paralelas à abscissa e à ordenada. Destes vértices, nós marcamos os que pertencem à relação.

### 3°. Matriz 0-1
Pode representar relações finitas, A relação R pode ser representada pela matriz MR(Lembrando de sempre colocar o símbolo da relação do lado do M) = [Mij]mxn, onde mij = (1), se ai e bj Estiverem relacionados ou = (0), se **aiRbj** for falso, ou seja, não estarem relacionados.

## Conceitos - Domínio, Imagem, Relação inversa
### Conceitos básicos:
Se (x,y) pertence à relação, dizemos que y é uma <mark style="background: #ABF7F7A6;">imagem</mark> de x através da relação. Além disso, nós podemos chamar x de um <mark style="background: #ABF7F7A6;">antecedente ou pré-imagem</mark> de y pela relação R.
### Domínio:
O domínio da relação R é a totalidade dos elementos de A, que <mark style="background: #FF5582A6;">admitem ao menos uma imagem em B</mark>. Ou seja, DR = {x em A: (x,y) em R}. em == pertence.
### Imagem:
A imagem de R é o conjunto dos elementos de B, que <mark style="background: #FF5582A6;">admitem pelo menos um antecedente em A</mark>. Isto é, IR = {y em A: (x,y) em R}.
### Inversa da relação:
A relação inversa pode ser representada como o subconjunto de <mark style="background: #FFB8EBA6;">B X A</mark> definido por: R^-1 = {(y,x): (x,y) em R}. Isto quer dizer que a relação R^-1 é apenas a <mark style="background: #BBFABBA6;">inversão dos pares ordenados</mark>, lembrando que a propriedade não necessariamente é invertida, apenas colocamos a <mark style="background: #FFB86CA6;">propriedade de acordo com y</mark>. Exemplo: R = {(x,y): x | y} -- R^-1 = {(y,x): y = k.x, para algum k em Z}.

## Operações entre relações (conjuntos)

### União:
A união entre uma relação R e uma relação S é a <mark style="background: #FFB8EBA6;">disjunção das duas relações</mark>, ou seja, ela contém tanto os pares ordenados que satisfazem R, quanto os elementos que satisfazem S. --> xRy ou xSy. 

Você pode representar isso em matrizes 0-1 e os elementos dessa matriz serão 1, caso aiRbj ou aiSbi ocorrerem e serão 0, caso o elemento não cumpra os requisitos.
### Intersecção:
A intersecção entre uma relação R e uma relação S é dada por: x(R^S)y = xRy e xSy, ou seja, <mark style="background: #ADCCFFA6;">as duas relações devem acontecer ao mesmo tempo</mark> para que, assim, o par ordenado pertence à intersecção das duas relações.

Da mesma forma da união, a intersecção pode ser representada na matriz 0-1, em que o elemento da matriz só vai ser 1, caso as duas relações sejam cumpridas e será 0, caso contrário.
### Complementar da relação:
A relação ~R(complemento de R) é dada por: (x,y) pertence a ~R, se, e somente se, (x,y) não pertence a R. Recordando que a relação complemento <mark style="background: #FFF3A3A6;">ocorre em A X B</mark>(mesmo conjunto universo de R).

Esse complemento também pode ser representado em forma de matriz. M~R = (~mij)mxn, em que ~mij(elemento) = 1, se ai não está relacionado com bj, e será igual a 0, caso contrário.

### Composição entre relações:
Seja R uma relação de A X B e S uma relação de B X C, então é possível definir uma relação entre A X C, chamada de composição entre R e S. Conforme: SoR={(x,z): existe ao menos um y em B, (x,y) em R e (y, z) em S} --> Você pode dizer que a composição utiliza o y como uma "ponte" entre a relação R e a relação S, dessa forma, partindo de A para C, se não existe esse elemento y, então não existirá composição das relações.

Podemos aplicar a operação de composição entre relações utilizando uma forma alternativa da multiplicação entre matrizes, em que você utiliza os operadores e/ou (o ^ representaria a multiplicação) e (o "ou" representaria a adição). 

Lembrando, número de colunas da primeira = número de linhas da segunda (Pra você multiplicar cada elemento de uma linha com cada elemento da outra coluna). Utilizando o método LICO, a matriz resultante da multiplicação possui o número de linhas da primeira matriz e o número de colunas da segunda matriz. O símbolo dessa operação entre matrizes é uma bola com um pontinho no meio.

```ad-attention
title: Atenção:
collapse: open
Na composição SoR, você parte do 1 elemento de um par ordenado de R para o segundo elemento de um par ordenado de S, ou seja, (x,y) em R  e (y,z) em S --> (x,z) em SoR. Por esse motivo, na maioria dos casos, SoR é diferente de RoS, pois a multiplicação entre matrizes não é comutativa. **SoR = Mr X Ms**
```
#### Propriedades:
- 1° - Associatividade
- 2° - (SoR)^-1 = R^-1 o S^-1 
- 3° - R^1 = R, R^2 = R o R, R^n+1 = R^n o R.


