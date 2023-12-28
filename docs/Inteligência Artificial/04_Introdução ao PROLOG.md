<center><h1>Prolog</h1></center>
Prolog é uma linguagem de programação, porém, diferente do JavaScript, Python, C++ e outras, essa linguagem não usa a logica computacional para gerar um valor ou criar uma saída, o Prolog usa uma lógica matemática para  avaliar a o dado ideal para o retorno da solicitação.

Essa estrutura é ideal para trabalhar com IA, para projetos mais aprofundado, é ideal usar um kit de ferramentas e um ambiente preparado para isso, mas para o estudo e a compreensão inicial, o Prolog ajuda muito.

<center><h2>Instalação</h2></center>

 A instalação do Prolog é bem simples, basta acessar o site, baixar o aplicativo e instalar, sem muito segredo. Para facilitar, basta clicar no [link](https://www.swi-prolog.org/download/stable/bin/swipl-9.0.4-1.x64.exe.envelope) que irá abrir a página do download para Windows

![[Download Prolog.png]]

Uma vez instalado, sua interface é bem simples.
![[Interface prolog.png]]

Como não criamos nenhum tipo de base de dados, não podemos usar ele ainda. Vamos criar nossa base para começar a ver como as coisas funcionam.

Siga o seguinte passo-a-passo:

Clicar em - File -> New -> digitar o nome do arquivo e selecionar o local para salvar -> Botão Salvar.

Isso abrirá uma janela em branco, igual a um bloco de notas, nesse ponto que iremos criar nossa base de dados.

Para editar este arquivos nós vamos usar alguns tipos de comandos, esses comandos tem nomes específicos para sua identificação:

* **Fato**: A cadeia de dados relacionado de pai/filho, dando a ordem e hierarquia do dado com seu titulo sendo o que da origem na informação, seguindo a seguinte estrutura:
	* NomeDoFato(DadoPai, DadoFilho) . (todo fato termina em "." ) ;
	* ex: Carro(Fiat, Palio);
* **Regra**: A regra é uma estrutura lógica, baseada em condições que ajudam o sistema a filtrar os dados:
	* NomeDaRegra(Y, X) :-
		 Carro(X, Y) .
	* Nesse exemplo, "X" é o DadoPai e "Y" é o DadoFilho, buscando a regra, é possivel achar o pai buscando o filho, sendo que normalmente, só conseguimos achar o filho depois e ter o valor do pai;
*  **Comentário**: Apenas uma instrução e um meio de organizar as informações:
	* Ex: % O texto na frente do porcentagem é um comentário, não é visco como dado;

Para fazer o nosso primeiro teste, vamos criar a seguinte estrutura de dados:

```prolog
% Carros
carro(fiat, palio);
carro(vw, gol);
carro(chevrolet, celta);
% Motos
moto(yamaha, fazer);
moto(honda, cg);
moto(suzuki, yes);
```

Após editar o arquivo, será necessário compilar ele para usarmos, para isso, basta clicar na aba "compile" e depois na opção "compile buffer".
![[Compilação prolog.png]]

E na janela principal aparecerá um texto em verde, confirmando o sucesso na compilação, sendo possível iniciar nossos comandos, que consiste em buscar um fato com a ausência de algum item, substituindo este item por "X" se for o PAI e "Y" se for o FILHO:
![[Uso prolog.png]]

Temos assim, nosso primeiro documento de dados do PROLOG.