<center><h1>DADOS</h1></center>
Para um contexto inicial, um DADO, nada mais é do que um fragmento de informação, ou seja, em uma palavra, a letra é um dado, para uma frase, uma palavra é um dado, para um preço, um número é um dado. Sempre que temos uma informação, ela é composta por vários dados, seguindo a seguinte estrutura:

* ***DADO*** = Letra, Número, ou item solto, sem relação com nada;
* ***Informação*** = A soma de vários DADOS, trazendo assim um valor para aqueles itens soltos e sem significado;
* ***Conhecimento*** = Acumulo de informação, guardada e organizada de forma a ser acessada facilmente e utilmente;
* ***Sabedoria*** = Ter proposito e utilidade para do conhecimento;

![[Estrutura de dados.png]]
<center>Pirâmide de dados</center>

Agora, sabendo como trabalhamos com a informação e como compor ela, vamos entender como funciona o armazenamento e a busca por esses dados e como isso se torna informação. O que precisamos entender aqui são as...

<center><h1>Estruturas de dados</h1></center>
... Que são:

*  ***Vetor*** : Funciona como uma estrutura ordenada, podendo ser identificada por pelo menos um índice;
*  ***Lista*** : A lista apresenta uma sequencia abstrata de valores, ordenada;
*  ***Pilha*** : Assim como empilhar objetos, esta estrutura usar o FILO(First In, Last Out), o primeiro a entrar é o ultimo a sair;
*  ***Fila*** : A fila, diferente da pilha, segue uma sequencia FIFO(First In, First Out), o primeiro a entrar é o ultimo a sair;
*  ***Arvore*** : Este é o que vamos usar, a arvore é uma estrutura ramificada, onde um dado, combinado e alinhado pode chegar a vários resultados lógicos possíveis;



O exemplo mais comum e simples de uma estrutura de dados em árvore é a arvore genealógica, que iremos apresentar a seguir de forma ilustrada e textual.

![[Estrutura de arvore.png]]

Com essa imagem podemos apresentar a seguinte descrição:

Pai = Jorge, ele tem dois filhos, Claudio e Ana.
Claudio também é pai de duas pessoas, ou seja, Claudio é filho de Jorge e pai de Samanta e Ricardo.
Ana é mãe de duas pessoas, sendo assim, como Claudio, Ana é filha de Jorge e mãe de Paulo e Pedro.

Usando esta descrição, montamos uma relação de Pai-Filho entre todos os dados recebidos.

Compreendendo isso, o nosso próximo passo é ir para a [[04_Introdução ao PROLOG]] e entender como aplicar essa lógica em um software de busca e estrutura de dados, a base para se criar uma IA.
