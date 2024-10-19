#Discreta 

## Definição: 
### Definição Informal:
Uma função é uma <mark style="background: #FFB86CA6;">"Regra"</mark> ou <mark style="background: #FFB86CA6;">'Mecanismo'</mark> que transforma uma grandeza/quantidade em outra.
### Definição Formal:
Uma relação F é chamada de função desde que (a,b) em F e (a,c) em F implique que <mark style="background: #FF5582A6;">a = c</mark>. Ou seja, um antecedente só pode possuir/gerar uma única imagem, assim, evitando ambiguidade. Algo a se observar é que geralmente usamos uma notação diferente dos pares ordenados para representar funções. **(1,2) <---> F(1) = 2**.
## Classificação:

### Função Injetora:
Uma função é injetora, ou injetiva, ou um para um, se sempre que (x, b) e (y, b) pertencerem à função, x = y, ou seja, as imagens da função terão um <mark style="background: #ADCCFFA6;">único antecedente</mark>, assim, evitando uma ambiguidade nas imagens. Em outras palavras, se x for diferente de y, então f(x) vai ser diferente de f(y), ou de forma equivalente, se **f(x) = f(y), então x = y**. 
Para provarmos que uma função não é injetora, basta apresentarmos um contraexemplo.

A partir dessa classificação, nós podemos afirmar que: <mark style="background: #D2B3FFA6;">F^-1 é uma função, se, e somente se, a função F for injetora</mark>.

Por fim, nós utilizaremos essa informação sobre as funções injetoras para conseguir transformar as relações inversas em funções, dessa forma, só resta igualar o domínio de F^-1 ao conjunto B. Para que, assim, f^-1 seja uma função de B para A.

---
### Função Sobrejetora:
Uma função é sobrejetora, se para todo b pertencente ao conjunto B, existe um 'a' pertencente ao conjunto A, tal que f(a) = b, ou seja, como todos os elementos do conjunto B possuem um antecedente em A, então <mark style="background: #BBFABBA6;">B = Im(F)</mark>. Assim, resolvendo o problema do domínio da função inversa. Basta provarmos que um elemento em B não possui um antecedente em A para que, assim, a função não seja sobrejetora.

### Função Bijetora:
Uma função de A -> B é <mark style="background: #D2B3FFA6;">bijetora</mark> quando ela é tanto <mark style="background: #D2B3FFA6;">sobrejetora</mark> quanto <mark style="background: #D2B3FFA6;">injetora</mark>, ou seja, as imagens só possuem um único antecedente em A e, além disso, para todo b pertencente ao conjunto B, existe ao menos um 'a' pertencente ao conjunto A, tal que f(a) = b, com isso, Im(F) = B. 

Uma observação importante é que: para que uma bijeção aconteça, ambos os conjuntos devem possuir a mesma cardinalidade, quantidade de elementos.

Algo importante de se comentar é o fato de que uma função só possuirá uma função inversa definida de um conjunto para outro, se ela for bijetora.

## Igualdade de funções:

Algo importante de se notar na igualdade de funções é que: duas funções só são iguais quando elas possuem a mesma <mark style="background: #ADCCFFA6;">propriedade de formação</mark> e elas possuem o <mark style="background: #ADCCFFA6;">mesmo domínio</mark>. Isso ocorre pelo fato de que quando nós temos um domínio diferente em uma função, nós podemos ter <mark style="background: #FF5582A6;">pares ordenados diferentes</mark> que pertencem a essa função, ou seja, elas se tornam funções/relações diferentes.

## Composição de Funções:

Sejam os conjuntos A, B e C e sejam f : A -> B e g: B -> C. Então, a função g o f é uma função de A para C, definida por (g o f)(a) = g(f(a)). Se lembre de que: quem fica mais à direita na função composta, é a função que se <mark style="background: #BBFABBA6;">relaciona primeiro</mark> com o objeto (a). Uma exigência que deve ser cumprida para que uma composta seja definida, é que <mark style="background: #FF5582A6;">a imagem da primeira função aplicada deve estar contida no domínio da segunda função</mark>.

Coisas interessantes de se notar sobre a função composta são que: o domínio dessa função está contido no <mark style="background: #FFB86CA6;">domínio da função mais interna</mark> e a imagem da função composta está contida na <mark style="background: #FFB86CA6;">imagem da função mais externa</mark>. Outra propriedade de funções compostas é que elas <mark style="background: #CACFD9A6;">não são comutativas</mark>.

Outro fato importante sobre as funções compostas é que elas possuem <mark style="background: #FFF3A3A6;">associatividade</mark>, ou seja, você pode mudar a posição dos parênteses. Assim, h o (g o f) = (h o g) o f.

### Função Identidade:

Seja A um conjunto, a função identidade em A é a função idA, cujo domínio é A e a imagem é A e para todo 'a' pertencente ao conjunto A, idA(a) = 'a'. Ou seja, idA = {(a,a), tal que 'a' pertence a A}. Nós podemos obter uma função identidade por meio da composição de funções, onde a função mais próxima da variável em composição com sua inversa faz uma <mark style="background: #FF5582A6;">função identidade no seu domínio</mark>.

Um fato interessante de se notar é que a composta de f o idA = idB o f = f;
	
![[Função-Identidade.png]]



## Contagem de Funções:

A contagem de funções é uma maneira de conseguirmos identificar de <mark style="background: #BBFABBA6;">quantas maneiras</mark>
nós podemos formar funções a partir de conjuntos fornecidos, podendo ser funções gerais/injetivas/sobrejetivas/bijetivas.

Ao todo, nós podemos fazer b^a funções --> f:A --> B com o conjunto A e B, de modo que, b = |B| e a = |A|. A notação para representar todas essas funções é o conjunto B^A que representa o conjunto de todas as funções f:A -> B.

Quantas funções injetoras nós podemos formar a partir de um conjunto A e um conjunto B? Lembrando que não podemos ter uma função injetora em que temos |A| > |B|, pois assim nós teríamos elementos de B que possuiriam mais de um antecedente, assim, rompendo com a injetividade. Nós podemos ter uma equivalência lógica dessa afirmação por contraposição também.

Para responder a questão anterior, nós podemos pensar na ideia de que vamos multiplicar as possibilidades a partir de b * (b-1) * (b-2) * ... * (b-(a-1)) = (b-a+1) - Nós não vamos até o (b-a), <mark style="background: #FFB8EBA6;">pois estaríamos multiplicando por 0</mark>, caso esses conjuntos tivessem a mesma cardinalidade. 

Ou seja, fazendo uma manipulação algébrica para deixarmos no <mark style="background: #FFB86CA6;">formato de Fatorial</mark>: temos a **b!/(b-a)!** escolhas. Nesse caso, nós vamos preenchendo os espaços e não repetimos as imagens.
	
Quantas funções sobrejetoras nós podemos formar a partir de um conjunto A e um conjunto B? Recordando que não podemos formar uma função sobrejetora em que |B| > |A|, pois assim nem todos os elementos de B teriam um antecedente em A, ou seja, não formaria uma função sobrejetora. Nós também podemos ter um equivalente lógico por  contraposição.

Neste caso, nós podemos utilizar o problema da <mark style="background: #FFB86CA6;">contagem de listas</mark>: Imagine que nós temos que escolher elementos de um conjunto com n objetos para compor uma lista de k espaços, assim, teríamos n^k possibilidades de fazer isto. Nós vamos pegar esse total de listas e <mark style="background: #FFF3A3A6;">subtrair as listas que nós não queremos</mark> para que, assim, conseguirmos chegar à <mark style="background: #FFF3A3A6;">lista que nós queremos</mark>.

![[SobrejetoraContagem.png]]

Quantas funções bijetoras podem ser obtidas a partir de um conjunto A e um conjunto B? Podemos afirmar que |A| = |B|. Se a = b, o número de funções sobrejetoras é **a! ou b!**.
## Extra:
### Formas de representação de funções:

#### - Gráficos:
Gráficos geralmente são utilizados em funções que possuem um conjunto contínuo, ou seja, o conjunto dos reais, que tem uma infinitude de elementos entre um elemento e outro. Mas, quando nós falamos de matemática discreta, isso não se torna tão interessante, visto que, nós ou utilizamos conjuntos, ou o conjuntos dos Naturais ou o conjunto dos Inteiros. Que não possuem uma continuidade interessante para se representar.
Assim, a representação por gráficos nesses contextos não fornece uma visão decente do panorama da função.

#### - Diagrama de Venn:
<mark style="background: #FF5582A6;">Principal método</mark> utilizado para representar as funções em conjuntos discretos(finitos).

### Tópicos relevantes:
- Nota relevante para a leitura do tópico: [[Relações]], [[Função Inversa]].

