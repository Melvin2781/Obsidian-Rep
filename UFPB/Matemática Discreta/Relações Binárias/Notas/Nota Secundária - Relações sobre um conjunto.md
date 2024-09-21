#Discreta 

## Definição:
	Sendo R uma relação entre A e B, em que A = B. Nesta situação, a relação está definida em A, e se identifica com um subconjunto de A² = A X A. Assim, para que R seja uma relação em A, R deve estar contido em A². Como todo subconjunto de A² é um elemento das partes de A², assim, podemos dizer que: R é uma relação sobre A se, e somente se, R pertence ao conjunto de partes de A². Ou seja, todos os subconjuntos de A² podem ser relação sobre A².

## Classificação:
	Seja R uma relação definida em A, isto é R está contida em A², podemos classificar ela segundo as seguintes propriedades:

### Reflexividade:
	A relação R é reflexiva, se, e somente se, para todo x em A, (x,x) pertence a R. Mais precisamente, a diagonal de A² deve estar contida na relação para que, assim, ela possa ser considerada reflexiva.
	Considerando essa relação na representação de matrizes, temos que R é reflexiva, se, e somente se, (ai,ai) pertence a R para i = 1, 2, ..., m. Ou seja, mii = 1, para i = 1, 2, ..., m. Em outras palavras, R é reflexiva se todos os elementos da diagonal principal da matriz forem igual a 1, do contrário a matriz não será reflexiva. 
	Quando você estiver na prova, lembre de que: para provar que uma relação não é reflexiva, nós precisamos dar mostrar que existe um x em A, tal que (x,x) não pertence à relação, ou seja, a intersecção entra a diagonal de A² e a relação é diferente de D(diagonal).

### Simetria:
	A relação R é simétrica se, e somente se, para todo x e y pertencentes a A, (x,y) em R implica (y,x) em R.
	Colocando essas informações em termos de matriz 0-1, R é simétrica, se, e somente se, (ai,aj) em R implica (aj,ai) em R. Dessa forma, Se mij = 1, então, mji = 1 e, por consequência, se mij = 0, então mji = 0. Juntando os dois enunciados, mji = mij, para todo i, j pertencentes ao conjunto {1, 2, 3, ..., m}.Em outras palavras, R é uma relação simétrica se, e somente se, MR é uma matriz simétrica, isto é, MR = transposta[MR].
	A partir desse conhecimento, já podemos analisar quando que uma relação é não simétrica, basta mostrarmos apenas um par ordenado que não cumpra com a implicação, dessa forma, resultando em uma matriz não simétrica.
	
### Transitividade:
	Uma relação R é transitiva, se, e somente se, para todo x,y e z pertencentes ao conjunto A, (x,y) em R E (y,z) em R implicam que (x,z) pertence a R, assim, caso a relação cumpra essas propriedades, ela será transitiva. 
	Lembrando que se x = y ou y = z, não vamos precisar verificar se a transitividade serve nesse caso, por exemplo: (2,2) e (2,3) --> x = y, logo, é óbvio que esses dois pares ordenados realizam a propriedade.
	OBS: R^1 = R, R^2 = R o R, R^n+1 = R^n o R.
	A partir dessa informação, existe um teorema que diz que a relação vai ser transitiva, se, e somente se, R^n estiver contido em R, para todo n = 1, 2, 3, ... .
	Passando essa relação para a sua representação matricial, para verificarmos que R é transitiva, precisamos calcular MR^2 = MR O MR --> Multiplicação matriz 0-1. Assim, R é transitiva se, e somente se, sempre que o elemento ij em MR^2 for diferente de zero, o elemento ij em MR também é diferente de zero. Mostrando que existe ao menos um elemento diferente de zero em MR^2 que não está em MR, a relação já é não transitiva.

### Antissimetria:
	A relação R é antissimétrica se, e somente se, para todo x e y, (x, y) em R e (y, x) em R implicam que x = y. Se existir o par ordenado (x, y) e não houver o par ordenado (y, x), a implicação continua sendo verdadeira, pois a primeira parte dela é falsa. Lembrando que antissimetria e simetria não são opostos, uma relação pode ter as duas propriedades, a exemplo da relação diagonal em A.
	Colocando isso no contexto das matrizes, temos que: R é antissimétrica se, e somente se, se (ai, aj) pertence a R e (aj, ai) está em R, então, ai = aj. Por consequência, se mij = i, com j diferente de i, então mji = 0, em outras palavras, R é antissimétrica se i diferente de j, então mij = 0 ou mji = 0. Podemos considerar que a relação é não antissimétrica se existir algum contraexemplo para a antissimetria.
	
## Fecho de relações:
	Sabemos que uma dada relação pode não ter a propriedade de reflexividade, transitividade ou simetria, no entanto, se R não possui alguma propriedade em particular, podemos adicionar a menor quantidade possível de pares relacionados em R até que se adquira a propriedade desejada. Assim, ao fazer a união dessa relação com esses pares ordenados, estamos trabalhando com uma relação diferente. Lembrando que você pode precisar fazer diversos fechos para obter a propriedade.

### Fecho reflexivo:
	Você adiciona pares ordenados até obter uma relação reflexiva, você pode fazer isso unindo a diagonal de A(x,x) com a relação.

### Fecho simétrico: 
	Você adiciona elementos até obter uma relação simétrica, você pode fazer isso adicionando os elementos da relação inversa(y,x).

### Fecho simétrico:
	O fecho transitivo de uma relalção binária R num conjunto A é a menor relação transitiva em A que contém R. O fecho transitivo é obtido pelas uniões sucessivas de R^i, com i começando em 1 e indo até o infinito.

## Subnotas:
[[Nota Terciária - Ordem Parcial]] 
[[Nota Terciária - Relações de equivalência]] 