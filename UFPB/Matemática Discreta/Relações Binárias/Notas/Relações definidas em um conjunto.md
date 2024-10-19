#Discreta 

## Definição:
Sendo R uma [[Relações|relação]] entre A e B, em que A = B. Nesta situação, a relação está <mark style="background: #BBFABBA6;">definida em A</mark>, e se identifica com um subconjunto de A² = A X A. Assim, para que R seja uma relação em A, R deve estar contido em A². Como todo subconjunto de A² é um elemento das partes de A², assim, podemos dizer que: R é uma relação sobre A se, e somente se, <mark style="background: #FFB86CA6;">R pertence ao conjunto de partes de A²</mark>. Ou seja, todos os subconjuntos de A² podem ser uma relação sobre A².

## Classificação:
Seja R uma relação definida em A, isto é, R está contida em A², podemos classificar ela segundo as seguintes propriedades:
### Reflexividade:
A relação R é reflexiva, se, e somente se, para todo x em A, <mark style="background: #CACFD9A6;">(x,x) pertence a R</mark>. Mais precisamente, a <mark style="background: #FFB86CA6;">diagonal de A</mark> deve estar contida na relação para que, assim, ela possa ser considerada reflexiva.

Considerando essa relação na representação de matrizes, temos que R é reflexiva, se, e somente se, (ai,ai) pertence a R para i = 1, 2, ..., m. Ou seja, mii = 1, para i = 1, 2, ..., m. Em outras palavras, R é reflexiva se todos os <mark style="background: #FFB8EBA6;">elementos da diagonal principal da matriz</mark> forem igual a 1, do contrário a matriz não será reflexiva. 

Quando você estiver na prova, lembre-se que: para provar que uma relação não é reflexiva, nós precisamos mostrar que existe um x em A, tal que **(x,x) não pertence à relação**, ou seja, a intersecção entra a diagonal de A e a relação é diferente de D(diagonal).
### Simetria:
A relação R é simétrica se, e somente se, para todo x e y pertencentes a A, <mark style="background: #ADCCFFA6;">(x,y) em R implica (y,x) em R</mark>.

Colocando essas informações em termos de matriz 0-1, R é simétrica, se, e somente se, (ai,aj) em R implica (aj,ai) em R. Dessa forma, Se mij = 1, então, mji = 1 e, por consequência, se mij = 0, então mji = 0. Juntando os dois enunciados, mij = mji, para todo i e j pertencentes ao conjunto {1, 2, 3, ..., m}. Em outras palavras, R é uma relação simétrica se, e somente se, MR é uma matriz simétrica, isto é, MR = transposta[MR].

A partir desse conhecimento, já podemos provar quando uma relação é não simétrica, basta mostrarmos apenas um par ordenado que não <mark style="background: #FF5582A6;">cumpra com a implicação</mark>, dessa forma, resultando em uma matriz não simétrica.
### Transitividade:
Uma relação R é transitiva, se, e somente se, para todo x, y e z pertencentes ao conjunto A, <mark style="background: #BBFABBA6;">(x, y) em R e (y, z) em R implicam que (x, z) pertence a R</mark>, assim, caso a relação cumpra essas propriedades, ela será transitiva. 

Lembrando que se x = y ou y = z, a <mark style="background: #FFB86CA6;">transitividade é algo trivial</mark>. Portanto, é óbvio que esses dois pares ordenados cumprem a propriedade.

A partir dessa informação, existe um teorema que diz que a relação vai ser transitiva, se, e somente se, R^n estiver contido em R, para todo n = 1, 2, 3, ... .

Passando essa relação para a sua representação matricial, para verificarmos que R é transitiva, precisamos calcular MR^2 = MR O MR, [[Relações#Composição entre relações|Composição de matrizes 0-1]]. Assim, R é transitiva se, e somente se, sempre que o elemento ij em MR^2 for diferente de zero, o elemento ij em MR também deve ser diferente de zero. Mostrando que existe ao menos um elemento diferente de zero em MR^2 que não pertence a MR, a relação já não é transitiva.
### Antissimetria:
A relação R é antissimétrica se, e somente se, para todo x e y, <mark style="background: #ADCCFFA6;">(x, y) em R e (y, x) em R implicam que x = y</mark>. Se existir o par ordenado (x, y) e não houver o par ordenado (y, x), a implicação continua sendo verdadeira, pois a primeira parte dela é falsa. Lembrando que antissimetria e simetria não são propriedades opostas, uma relação pode ter as duas propriedades, a exemplo da relação diagonal em A.

Colocando isso no contexto das matrizes, temos que: R é antissimétrica se, e somente se, se (ai, aj) pertence a R e (aj, ai) está em R, então, ai = aj. Por consequência, se mij =1, com j diferente de i, então mji = 0. Em outras palavras, para que R seja antissimétrica, no caso de i ser diferente de j, um dos pares não pertence ou os dois pares não pertencem à relação. É necessário apenas um contraexemplo para dizer se uma matriz não é antissimétrica.
## Fecho de relações:
Sabemos que uma dada relação pode não possuir a propriedade de reflexividade, transitividade ou simetria, no entanto, se R não possui alguma propriedade em particular, podemos <mark style="background: #ADCCFFA6;">adicionar a menor quantidade possível</mark> de pares relacionados em R, até que se adquira a propriedade desejada, ou seja, a realização de um fecho. Assim, ao fazer a união da relação de origem com esses pares ordenados, obteremos uma <mark style="background: #FF5582A6;">relação diferente que contém a relação original</mark>. Lembrando que pode ser necessário <mark style="background: #FFB86CA6;">diversos fechos</mark> para obter a propriedade desejada.

### Fecho reflexivo:
Você adiciona pares ordenados até obter uma <mark style="background: #FFB8EBA6;">relação reflexiva</mark>, você pode fazer isso unindo a <mark style="background: #FFB86CA6;">diagonal de A </mark>com a relação original. Também chamada de identidade de A.

### Fecho simétrico: 
Você realiza o fecho simétrico a partir da adição de elementos na relação, até que seja possível obter uma <mark style="background: #FF5582A6;">relação simétrica</mark>, isso pode ser realizado por meio da adição dos elementos da [[Relações#Inversa da relação|relação inversa]] (y, x) R^-1.

### Fecho Transitivo:
O fecho transitivo de uma relação binária R em um conjunto A é a menor relação transitiva, em A que contém R. O fecho transitivo é obtido pelas <mark style="background: #FFB86CA6;">uniões sucessivas</mark> de R^i, com i partindo de i e podendo chegar até o infinito. Lembre-se da propriedade do fecho transitivo em relação à cardinalidade do conjunto. Faremos um <mark style="background: #FFB8EBA6;">somatório da união</mark> de R^k, com k começando como 1 e indo até |A|.