#Discreta
## Definição: 
	Uma relação entre A e B é um subconjunto do produto cartesiano A X B. Ou seja, R é uma relação entre A e B, se, e somente se, R está contido no conjunto AXB.
	
## Símbolos para representar a relação:
	Nós podemos utilizar a notação aRb para indicar que o par ordenado (a,b) pertence à relação. Lembrando que o par ordenado só pertence à relação se ele pertencer ao produto cartesiano AXB e se ele cumprir a proposição de R.
	

## Maneiras de representar as relações(Finitas):
### 1°. Diagrama de Venn
	Nós podemos utilizar diagramas de Venn, que nem a representação de funções, mas, nesse caso, nós podemos enviar mais de uma setinha do conjunto A(Conjunto que contém o domínio) para o conjunto B(Conjunto que contém o conjuto imagem)

### 2°. Gráfico cartesiano
	Nesta representação em gráfico, a abcisa é o primeiro conjunto do produto cartesiano e a ordenada é o segundo conjunto do produto cartesiano. Os elementos do produto cartesiano A X B, são os vértices dos quadrilateros formados pelas retas paralelas à abcisa e à ordenada. Destes vértices, nós marcamos os que pertencem à relação.

### 3°. Matriz 0-1
	Pode representar relações finitas, A relação R pode ser representada pela matriz MR(Lembrando de sempre colocar o símbolo da relação do lado do M) = [Mij]mxn, onde mij = (1), se aiRbj -- > Estiverem relacionados ou = 0, se aiRbj for falso, ou seja, não estarem relacionados.

## Conceitos - Domínio, Imagem, Relação inversa
### Conceitos básicos:
	Se (x,y) pertence à relação, dizemos que y é uma imagem de x através da relação. Além disso, x é um antecedente ou pre-imagem de y pela relação.

### Domínio:
	O domínio da relação R é a totalidade dos elementos de A, que admitem pelo menos uma imagem em B. Ou seja, DR = {x em A: (x,y) em R}. em -- pertence;

### Imagem:
	A imagem de R é o conjunto dos elementos de B, que admitem pelo menos um antecedente em A. Isto é, IR = {y em A: (x,y) em R}.
	
### Inversa da relação:
	A relação inversa pode ser representada como o subconjunto de B X A definido por: R^-1 = {(y,x): (x,y) em R}. Isto quer dizer que o conjunto R^-1 é apenas a mudança de x e y para y e x.

## Operações com relações(Operações de conjunto)

### União:
	A união entre uma relação R e uma relação S é a disjunção das duas relações, ou seja, ela contém tanto os pares ordenados que satisfazem R, quanto os elementos que satisfazem S. --> xRy ou xSy. 
	Você pode representar isso em matrizes 0-1 e os elementos dessa matriz serão 1, caso aiRbj ou aiSbi acontecerem e serão 0, caso o elemento não cumpra os requisitos.

### Intersecção:
	A intersecção entre uma relação R e uma relação S é dada por: x(ReS)y = xRy e xSy, ou seja, as duas relações devem acontecer ao mesmo tempo para que, assim, o par ordenado pertence à intersecção das duas relações.
	Da mesma forma da união, a intersecção pode ser representada na matriz 0-1, em que o elemento da matriz só vai ser 1, caso as duas relações sejam cumpridas e será 0, caso contrário.

### Complementar da relação:
	A relação ~R(complemento de R) é dada por: (x,y) pertence a ~R, se, e somente se, (x,y) não pertence a R. Recordando que a relação complemento ocorre em A X B(mesmo conjunto universo de R).
		Esse complemento também pode ser representado em forma de matriz. M~R = (~mij)mxn, em que ~mij(elemento) = 1, se ai não está relacionado com bj, = 0, caso contrário.

### Composição entre relações:
	Seja R uma relação de A X B e S uma relação de B X C, então é possível definir uma relação entre A X C, chamada de composição entre R e S. Conforme: SoR={(x,z): existe ao menos um y em B e (x,y) em R e (y, z) em S} --> Você pode dizer que a composição utiliza o y como uma ponte entre a relação R e a relação S, dessa forma, partindo de A para C.
	Podemos aplicar a operação de composição entre relações utilizando uma forma alternativa da multiplicação entre matrizes, em que você utiliza os operadores e/ou (o e representaria a multiplicação) e (o ou representaria a adição) -- Lembrando número de colunas da primeira = número de linhas da segunda (Pra você multiplicar cada elemento de uma linha com cada elemento da outra coluna). Utilizando o método LICO, a matriz resultante da multiplicação possui o número de linhas da primeira matriz e o número de colunas da segunda matriz. O símbolo dessa operação entre matrizes é uma bola com um pontinho no meio.

#### Propriedades:
##### 1°. - Associatividade

##### 2°. (SoR)^-1 = R^-1 o S^-1 

## Subnotas:
[[Subnota - Relações sobre um conjunto]] 


