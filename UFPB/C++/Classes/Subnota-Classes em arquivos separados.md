#CPP 
## Utilidade:
	Quando nós temos muitas classes, pode ser interessante utilizarmos classes em diferentes arquivos, com o intuito de diminuir o excesso de código em um único arquivo.

## Como utilizar:
	Nós podemos criar classes em arquivos diferentes por meio da divisão dos códigos em arquivos de tipos diferentes, uma arquivo para apenas apresentar os nomes das classes, classe.h --> Meio que uma biblioteca. --> Você coloca apenas o nome das classes e seus parâmetros, sem colocar o bloco.
	
	Um arquivo para escrevermos o bloco de cada função, indicando para que elas servem. ---> Você chama a biblioteca que você criou em C++ e coloca o corpo de cada função. --> Você pode dar include na biblioteca por meio da sintaxe: #include "carro.h" --> Usando o "" para indicar que você criou essa biblioteca.
	
	E um arquivo main, onde nós podemos escrever o código já utilizando a função. --> Faça o código principal nesse arquivo. Lembre de dar include no carro.h nesse arquivo também.
	
	Com isso, você vai precisar compilar os dois arquivos ao mesmo tempo --> carro.cpp e main_carro.cpp. Para que, assim, o código rode tranquilamente.


OBS: Você precisa usar o comando g++ main_carro.cpp carro.cpp -o carro.exe para compilar os dois arquivos. Lembrando do espaço entre os arquivos e utilizando o -o para escrever o nome do arquivo que você quer gerar após a compilação. 

OBS2: Você pode utilizar outra forma para compilar os dois arquivos juntos, por meio do cmd. Usufruindo da navegação por meio do cd e no fim fazendo a mesma coisa que no terminal do visual Studio, dessa forma, você não vai precisar colocar o system("pause").

## Sintaxe vscode:

**pwd** - Informa o diretório em que você está.
**ls** - Dá uma lista de todos os arquivos que estão em seu diretório.
**cd** - Permite com que você navegue para outra pasta. -- cd aula17. - Se você quiser voltar para uma pasta anterior utilize: cd.. .
[Fonte](https://terminalcheatsheet.com/pt-BR/guides/navigate-terminal#:~:text=Assim%20que%20você%20abrir%20o,seu%20diretório%20de%20trabalho%20atual.) 