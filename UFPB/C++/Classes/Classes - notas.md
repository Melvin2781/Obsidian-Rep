#CPP
## Definição:
	Classes são utilizadas para criar objetos com características em comum e criar uma biblioteca de funções. - Lembrando, quando você for declarar um classe, coloque o ponto e vírgula logo após o fechamento das chaves.
## Propriedades:
	Funções(Métodos)/Variáveis(Membros) públicas ou privadas: Funções/Variáveis podem ser públicas(podem ser utilizadas em qualquer local do seu código, ou seja, é possível utilizá-las na main) ou privadas(só podem ser utilizadas dentro da classe ou em instâncias da classe). Funções muito comuns são a função Get(Obter alguma variável) e a função Set(Setar alguma variável). Por fim, as variáveis de uma classe geralmente ficam no private.

## Chamada:
	Toda vez que você fizer a chamada de uma classe, você precisa dar um nome para um objeto. Para você usar as funções da classe, você precisa utilizar o objeto para que as funções funcionem. --> canal.função(); .
	
## Função Construtor:
	É uma função em que, quando criamos um objeto, já começamos fazendo algo nele. Nesse tipo de função, não há um tipo de saída, nós começamos essa função com o nome da própria classe. 
	Ou seja, você inicializa um objeto com algumas propriedades já definidas. Você consegue estabelecer valores padrões, caso nenhum valor tenha sido apresentado na entrada. Dessa forma, quando você criar um objeto, essa função será chamada. --> Lembrando, você precisa definir logo no início seus parâmetros, a não ser que você tenha um construtor padrão.
	
## Extra:
OBS1: Dentro da classe, você pode utilizar o this -> elemento = elemento, quando você possui duas variáveis com o mesmo nome. Dessa forma, você pode atribuir valores às propriedades do objeto de uma certa classe.

OBS2: Você pode fazer a definição de uma classe e suas funções em arquivos diferentes, ou seja, você vai utilizar a prototipação de funções, extern e essas coisas. Assim, você pode colocar as funções abaixo do main. Utilizando o carro:: depois do tipo da função. Algo que é bem parecido com o std:: das funções cout e cin. --> Representa de qual biblioteca você está utilizando.

OBS3: Dentro de classes, você pode chamar funções de métodos.

[[Subnota-Classes em arquivos separados]] 

![[Explicação-chatgpt.png]]![[chatgpt-considerações finais.png]]![[Chatgpt-considerações-finais-2.png]]![[Lista de inicialização.png]]