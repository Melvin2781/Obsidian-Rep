---
Assunto: Indução Matemática
Dependências: "[[Ordem Parcial - Total]]"
---
#Discreta 

## Definição:

### Definição Informal:

	Nós podemos utilizar o efeito cascata em uma fila de peças de dominó para exemplificar a indução matemática, em que, quando o primeiro dominó cai, as peças mais próximas começam a cair uma após a outra.

### Definição Formal:

	Nesse contexto, podemos expressar esse fenômeno informal em uma linguagem mais formal ou seja, iremos apresentar uma definição que utiliza a linguagem matemática a partir de duas propriedades:
* a) a primeira peça é derrubada em direção às outras peças.
* b) Caso alguma peça esteja próxima o suficiente da sua vizinha consecutiva, então, ao ser derrubada, fará com que a sua vizinha consecutiva também seja derrubada.

## Princípios da Indução:

```ad-important
title: Importante
collapse: open

* A prova por Indução pode ser chamada de Princípio de Indução Matemática ou Princípio da Indução Finita.
* É uma técnica utilizada para lidar com tipos de dados que pertencem a conjuntos bem-ordenados.
* Dada uma relação de boa-ordem, pode-se aplicar indução para provar propriedades que valem para todos os elementos de um tipo de dado.
* Para facilitar a vida dos alunos, em matemática discreta, utilizaremos apenas o conjunto dos números naturais e a relação de menor igual.
```
## Teorema utilizado na indução:


![[Demonstração Indução.png]]
![[Demonstração Indução 2.png]]

## Roteiro da Prova por Indução:

	Para provar que uma propriedade é verdadeira para todos os n's pertencentes ao conjunto dos naturais, nós precisamos seguir um certo roteiro para que, assim, fique mais fácil de organizar essas demonstrações.
	 Nesse caso, nós utilizaremos as duas demonstrações anteriores como base para as demonstrações por indução. Principalmente o princípio fraco da indução matemática:

* 1. Etapa Básica: Você precisa provar que P(1) é verdadeira. - Nunca se esqueça de realizar esse passo, pois ele é extremamente importante para decidir se você continuará ou não na indução.
* 2. Etapa Indutiva Você precisa provar que: 
	* 2.0 P(h) é verdadeira, então P(h+1) também é verdadeira, mais precisamente:
	* 2.1 Hipótese da Indução: Suponha que o resultado é verdadeiro para n = h.
	* 2.2 Tese: Usando a hipótese da indução, prove que o resultado é verdadeiro para n  = h + 1.
 * 3 Etapa Geral: Portanto, o resultado será verdadeiro para todos os números naturais, ou seja, P(n) é verdadeiro para todo n pertencente ao conjunto dos números naturais. Isso ocorre devido ao princípio fraco da indução.