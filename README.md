<p align="center">
<img src="resources/img/capa.png">
</p>
<hr>

<br /><br />

<p align="center">
© 2017 by Bruno Luvizotto Carli
</p>

<br />

<p align="center">
<img src="resources/img/cc1.png">
</p>

<br />

<p align="center">
<img src="resources/img/cc2.png">
</p>

<br />

<p align="center">
Esta obra é licenciada sob a Licença Creative Commons
Atribuição–Não Comercial 2.5 Brasil. Você pode
compartilhar e adaptar o conteúdo deste material desde
que os devidos créditos sejam dados ao autor do trabalho.
Para ver uma cópia desta licença, visite
http://creativecommons.org/licenses/by-ncsa/2.5/br/ ou
envie uma carta para Creative Commons, 171 Second
Street, Suite 300, San Francisco, California 94105, USA.
</p>

<hr>

<p align="center">
Índices para catálogo sistemático:
</p>

<p align="center">
1. Computadores: Programação;
2. Programação de computadores;
3. Algoritmos;
4. Linguagem de Programação;
</p>
<hr>

<br /><br /><br /><br />

<p align="center">
2˚ Edição
</p>

<br /><br />

<hr>
CAPA: Bruno L. Carli.
Adaptado de: https://pixabay.com/pt/animal-a-fotografiaanimal-close-up-1853944/
<hr>

<br /><br /><br /><br /><br /><br /><br />

<p align="center">Contato: brunolcarli@gmail.com</p>

 <br /><br /><br /><br /><br /><br /><br /><br /><br /><br />

 <hr>

<br /><br /><br /><br /><br /><br /><br />
<p align="center">BRUNO LUVIZOTTO CARLI</p>

<br /><br /><br /><br /><br /><br />

<p align="center">
Algoritmos e lógica de
programação com Python
</p>

<br /><br /><br /><br /><br /><br />

<p align="center">2˚ Edição </p>

<br /><br /><br /><br /><br /><br />

<p align="center">Curitiba, PR</p>
<p align="center">Edição do Autor</p>
<p align="center">2018</p>

<br /><br />

<hr>

<br /><br /><br /><br /><br /><br />
<br /><br /><br /><br /><br /><br />

> <small>Para meu pai, que me disse
que computação era besteira...</small>

<br /><br /><br /><br /><br /><br />
<br /><br /><br /><br /><br /><br />

<hr>

<br />

# Sumário

__inprogress

* [Apresentação](#apresentacao)
* [Capítulo 1](#capitulo-1)
    - [Conceito de Algoritmo](##conceito-de-algoritmo)
    - [Algoritmos para a lógica de programação](##algoritmos-para-a-logica-de-programacao) 
    - [Tipos de algoritmo](##tipos-de-algoritmos)
    - [Python](##python)
* [Capítulo 2](#capitulo-2)
    - [Construindo algoritmos com Python](##construindo-algoritmos-com-python)
    - [Variáveis e tipos de dados](##variaveis-e-tipos-de-dados)
    - [Variáveis em Python](##variaveis-em-python)
    - [Constantes](##constantes)
    - [Expressões](##expressões)
    - [Funções Intrínsecas](##funcões-intrinsecas)



# Apresentação

<p align="justify">
Olá amigo leitor, nesta obre pretendo elucidar conceitos
básicos, porém fundamentais ao aprendizado da lógica de
programação e o entendimento acerca da elaboração de
algoritmos. Você será inicialmente apresentado à alguns
exemplos de tipos de algoritmos e imerso na conceituação
implícita do que é um algoritmo. Vamos ser apresentados à
poderosa linguagem de programação Python, nossa principal
ferramenta para implementação de algoritmos no decorrer
deste livro.
</p>
<p align="justify">
Saliento desde já que esta obra não pretende ser mais
um livro para o ensino da linguagem de programação Python,
pretendo com este manuscrito apresentar os conceitos básicos e
fundamentais dos algoritmos e lógica de programação como os
tipos de dados, características de um algoritmo, estruturas de
dados laços de repetição sub-rotinas e manipulação de arquivos
permanentes, ao mesmo tempo em que possa induzir você
leitor a conhecer e utilizar o Python para implementação dos
nossos programas, e se você caro leitor se identificar
positivamente com o Python, insisto que busque na farta bibliografia literária disponível abordando os mais diversos
conceitos técnicos sobre Python.
</p>
<p align="justify">
Este livro objetiva orientar e colaborar no estudo dos
algoritmos e lógica de programação de iniciantes no estudo da
computação, hobbystas iniciantes e alunos de cursos técnicos e
graduações que estejam começando nesta magnifica área que é
a programação de computadores. Ressalto que este não é um
livro orientado ao ensino de Python e espera-se de você leitor
que compreenda os fundamentos da lógica de programação
podendo facilmente adaptar os exemplos demonstrado nesta
obra em outras linguagens de programação sem muita
dificuldade.
</p>

<br />
- O autor.

<br /><br />

<hr>

<br /><br />

# Capítulo 1

## Conceito de Algoritmo

<p align="justify">
Quando falamos em algoritmo é comum pensar em algo
relacionado à matemática, o que de certa forma não está errado, pois quando pequenos na escola primária éramos incitados a resolver diversas contas utilizando algoritmos matemáticos necessários à resolução dos exercícios. Puga e Rissetti (2010,
p. 9) comentam que “A matemática clássica é, em grande parte o estudo de determinados algoritmos”, isso pode a uma primeira vista assustar iniciantes no estudo da lógica de programação, mas vale salientar que não necessariamente o estudo de algoritmos envolve o estudo da matemática.
</p>

<p align="justify">
Para Puga e Rissetti (Op cit.) um algoritmo nada mais é que “uma sequência lógica de instruções que devem ser seguidas para a resolução de um problema ou execução de uma tarefa”. Ascencio e Campos (2010, p.2) vão ainda mais profundamente na conceituação de algoritmos citando diversas fontes definindo o que são algoritmos, dentre algumas pode-se
citar: “sequência de passos que visa atingir um objetivo bem definido” (FORBELLONE, 1999 apud ASCENCIO; CAMPOS, 2010), “sequência finita de instruções ou operações cuja execução, em tempo finito, resolve um problema computacional, qualquer que seja sua instância” (SALVETTI, 1999 apud ASCENCIO & CAMPOS, 2010).
</p>

<p align="justify">
Etimologicamente, de acordo com Abbagnano (2007, p.
27), a palavra Algoritmo deriva do nome de Mohammed alKhuwarizmi que foi um astrólogo e matemático árabe do século IX, responsável por introduzir o sistema de numeração indiano no Ocidente, esta notação durante a Idade Média tornou-se conhecida como algorísmos, sendo conhecida hoje pelo sistema numérico decimal que utilizamos no nosso dia a dia.
</p>

<p align="justify">
Para finalizar a conceituação de algoritmo de uma
forma, simples e entendível, um algoritmo é um passo a passo ou ainda, uma sequência de instruções para se chegar a um determinado objetivo, simples assim. Para exemplificar vamos demonstrar um algoritmo de uma tarefa corriqueira que todos fazemos diariamente: Beber água.
</p>

*Passo a passo para beber água:*

1. Pegar um copo ou recipiente;
2. Colocá-lo sob a torneira ou filtro de água;
3. Abrir a torneira/filtro;
4. Quando o copo estiver suficientemente cheio, fechar a
torneira/filtro;
5. Beber a água do copo/recipiente;

<p align="justify">
Simples, não é? Pode-se perceber que não temos nada
de muito matemático nisso, é um simples passo a passo, ou ainda, uma sequência finita de instruções que são seguidas para realizar uma tarefa (beber água). Vale-se ressaltar que não existe uma única forma de beber água, poderia-se beber água da fonte ou de um rio utilizando as mãos ou outros procedimentos, e isso é válido para todos os algoritmos, pois podem haver diferentes formas de realizar uma mesma tarefa desde que respeitem a lógica do processo, a exemplo disso pode-se dizer que não seria coerente fechar a torneira para depois colocar o copo abaixo da torneira para encher. Vamos demonstrar um outro exemplo de algoritmo: Uma ligação
telefônica.
</p>

*Passo a passo para realizar uma ligação:*

1. Pegar o telefone;
2. Inserir o número para quem deseja-se telefonar;
3. Aguardar ser atendido;
4. Depois de realizar a conversação, colocar o telefone no gancho (ou apertar o botão de desligar no caso de alguns telefones);

## Algoritmos para a lógica de programação

<p align="justify">
Certo, já sabemos o que são algoritmos e de onde essa
palavra surgiu. Mas e a relação entre os algoritmos e a programação de computadores?
</p>

<p align="justify">
Os computadores não compreendem instruções humanas como estas citadas anteriormente, os computadores só conhecem um tipo de linguagem: binária (zeros e uns) ou como define Tanenbaum (2010, p. 1) linguagem de máquina, mas se acalme, não há necessidade de se tornar um expert em linguagem binária para programar um computador, para isso existem as linguagens de alto nível ou linguagens de programação, que de acordo com Pressman (2010, p. 677) “são veículos de comunicação entre os seres humanos e os computadores”, as quais permitem que o programador possa elaborar um roteiro de instruções passo a passo (algoritmo) para que o computador execute uma determinada tarefa, estas linguagens de alto nível ou popularmente conhecidas como linguagens de programação, das quais pode-se citar o C, C++, Java, Cobol, Fortran, Python, dentre muitas outras linguagens existentes. Cada linguagem possui sua própria estrutura sintática porém sua essência reside na coerência lógica em que as instruções são fornecidas ao computador, sendo assim, o algoritmo escrito em uma linguagem de programação recebe o nome de programa (TANENBAUM, 2010).
</p>

## Tipos de algoritmo

<p align="justify">
Os algoritmos podem ser descritos em diferentes
formas, Ascencio e Campos (2010, p.3-4) apresentam a
Descrição Narrativa, o Fluxograma e o Pseudocódigo. Cada um desses será analisado nesta seção:
</p>

*Descrição Narrativa*
<p align="justify">
A descrição narrativa já foi apresentada no início deste capitulo, nos exemplos de beber água e no exemplo de realizar uma ligação telefônica. Consiste em descrever em linguagem natural a sequência de eventos que se sucederão. Vamos exemplificar com mais um algoritmo em descrição narrativa:
</p>

Somar dois números:

1. Definir o primeiro número;
2. Definir o segundo número;
3. Realizar a operação de soma entre os dois números;
4. Obter e demonstrar o resultado;

<p align="justify">
Esse tipo de algoritmo nos lembra muito de receitas de
bolo por exemplo, porém possui uma grande desvantagem, por se tratar de uma linguagem natural, suas instruções podem ser ambíguas abrindo espaço para diferentes interpretações, dificultando sua transcrição em programa(ASCENCIO; CAMPOS, 2010), fazendo com que este modelo de algoritmo
não seja muito utilizado em programação.
</p>

*Fluxograma*

<p align="justify">
O fluxograma é uma forma de representar a sequência
de instruções através de figuras geométricas, sendo elas: 
</p>

<p align="center">
Tabela 1 – Símbolos utilizados no fluxograma e seus significados
</p>

<p align="center">
<img src="resources/img/tabela1.png">
</p>

<p align="center">
Fonte: Ascencio & Campos (2010, p. 4)
</p>

<p align="justify">
Vamos exemplificar a utilização do fluxograma em um
algoritmo cujo objetivo é realizar a soma de dois números, o mesmo algoritmo apresentado anteriormente:

<p align="center">
Figura 1. Fluxograma representando um algoritmo para soma de dois números
</p>

<p align="center">
<img src="resources/img/fig1.png">
</p>

<p align="center">
Fonte: O autor.
</p>

<p align="justify">
As desvantagens do fluxograma segundo Ascencio e
Campos(2010) são a necessidade de aprender os significados dos símbolos do fluxograma, que muitas vezes podem diferir, como por exemplo podemos ver na Figura 2 duas representações diferentes para o símbolo de saída de dados. Outra desvantagem apresentada é que o fluxograma não apresenta muitos detalhes, o que também dificulta a implementação deste algoritmo em um programa de computador.
</p>

<p align="center">
Figura 2: Representações para a Saída de Dados
</p>

<p align="center">
<img src="resources/img/fig2.png">
</p>

<p align="center">
Fonte: Figura do lado esquerdo, Ascencio & Campos (2010). Figura do lado direito, Puga &
Rissetti (2010).
</p>

*Pseudocódigo*

<p align="justify">
O Pseudocódigo, também conhecido como Portugol
(ASCENCIO; CAMPOS, 2010) ou Português Estruturado
(PUGA; RISSETTI, 2010) é um modelo de algoritmo muito
semelhante a um código escrito em linguagem de programação de alto nível, tornando sua implementação em um programa uma tarefa muito simples para o programador. Para Puga e Rissetti (2010, p. 11) este é uma representação de algoritmo em uma linguagem intermediária entre linguagem de programação
e a linguagem natural humana, mais especificamente, o nosso Português. De acordo com Puga & Rissetti (Op. Cit.) o nome “Pseudocódigo” significa “falso código”, justamente por ser extremamente parecido com um algoritmo implementado em linguagem de alto nível. Vamos ver o mesmo exemplo anterior (soma de dois números) representado em Pseudocódigo:
</p>

    ALGORITMO: soma
    VAR
        num1, num2, soma : Inteiro
    INICIO
        LEIA(num1)
        LEIA(num2)
        soma ← num1 + num2
        ESCREVA(soma)
    FIM.

<p align="justify">
Este exemplo pode ser facilmente transcrito em
qualquer linguagem de programação e executado por um
computador. Vamos analisar a estrutura do pseudocódigo:
</p>

<p align="center">
Tabela 2 – Estrutura do pseudocódigo
</p>

| Psudocódigo | Descrição |
| ------------- | ------------- |
| ALGORITMO: soma | Esta primeira seção declara o nome do algoritmo |
| VAR: num1, num2, soma : inteiro | Esta seção é chamada de declaração de variáveis, onde todas as variáveis que serão utilizadas no algoritmo devem ser fornecidas, neste caso precisamos de três delas, o primeiro número, o segundo número e o resultado da soma. Todas elas são do tipo inteiro então declaramos uma após a outra, separando-as por vírgulas. Veremos mais sobre variáveis mais adiante.|
| INICIO LEIA(num1) LEIA(num2) soma ← num1 + num2 ESCREVA(soma) FIM |  Esta seção é o corpo principal do algoritmo, onde todas as instruções serão declaradas. Neste caso temos duas instruções, LEIA( ) e ESCREVA( ). A instrução LEIA( ) é um comando de entrada de dados, o que significa que um valor será fornecido para a variável num1 e num2. Então temos a atribuição do resultado para a variável soma, esta atribuição é representada pelo simbolo “← “. O comando ESCREVA( ) representa uma saída de dados, que neste caso demonstra a exibição do valor guardado na variável “soma”. FIM. Indica que chegamos ao fim do algoritmo. |


<p align="center">
Fonte: O autor.
</p>

<p align="justify">
Algumas desvantagens do pseudocódigo apresentadas
por Ascencio e Campos (2010) é que deve-se aprender as
regras do pseudocódigo, da mesma forma que se aprenderia os
significados dos símbolos do fluxograma ou as regras sintáticas
de uma linguagem de programação, além do mais não é
possível implementar programas reais em pseudocódigo, por
estes motivo vamos conceber a linguagem de programação
Python como forma de implementação e aprendizado dos
nossos algoritmos por sua facilidade de compreensão, ao final
deste livro você não somente saberá os princípios básicos da
construção e interpretação de algoritmos assim como terá os
conhecimentos básicos de uma poderosa linguagem de
programação e estará escrevendo seus próprios programas de
computador.
</p>

## Python

><small>Python é uma linguagem extremamente eficiente: seus programas farão mais com menos linhas de código, se comparado ao que muitas outras linguagens exigiriam. A sintaxe de Python também ajudará você a escrever um código “limpo”. Seu código será fácil de ler, fácil de depurar, fácil de estender e de expandir, quando comparados com outras linguagens. (MATTHES, 2016. p. 28) </small>

<p align="justify">
Para a metodologia deste livro, pretende-se utilizar a
Linguagem Python como forma de aprendizado de algoritmos,
visto que as formas mais populares de algoritmos apresentam
desvantagens relacionadas ao aprendizado das regras próprias
de cada modelo, utilizaremos a Linguagem de Programação
Python por sua alta legibilidade, o que quer dizer que um
programa escrito nesta linguagem é facilmente compreendido,
sem haver muito esforço da parte do programador em entender
seus comandos, além do mais, um algoritmo implementado em
Python é facilmente executado em qualquer sistema
operacional com um interpretador Python instalado. Isto
possibilitará aos iniciantes na lógica de programação não
somente a compreender a implementação dos algoritmos mas
também a familiarizar-se com as regras de uma simples, porém
extremamente poderosa linguagem de programação de
propósito geral, permitindo que escreva programas eficientes
com poucas linhas de comando em qualquer ambiente
operacional. Finalizando esta justificativa, é fundamental no
aprendizado de algoritmos que se pratique muito, e nada
melhor do que ver resultados instantâneos através de atividades
práticas, logo o Python se demonstrará uma excelente
ferramenta para se iniciar no mundo da programação, então
vamos colocar a mão na massa.
</p>

<p align="justify">
Primeiramente será necessário a instalação de um
Interpretador Python no seu computador, o download pode ser
feito pelo website oficial do Python:
<https://www.python.org/downloads/>.
</p>

<p align="justify">
O Python é disponibilizado em duas versões, Python 2.x
e Python 3.x, não tendo grandes diferenças entre si, porém para
fins de praticidade recomenda-se que o leitor utilize a mesma
versão apresentada no livro, neste caso utilizaremos a versão
Python 3.x, mais especificamente 3.5.2. Qualquer versão do
Python 3.x poderá ser utilizada para executar os algoritmos
deste livro.
</p>

<p align="justify">
Após fazer o download e instalação do Python 3 para o
seu Sistema Operacional você notará que um editor chamado
“IDLE” foi instalado juntamente com sua versão do Python.
</p>

><small>Quando você instala o Python 3, também terá o
IDLE, o ambiente simples – mas surpreendentemente útil – de desenvolvimento integrado do Python. O IDLE inclui um editor de destaque da sintaxe, um depurador, o Python Shell e uma cópia completa do conjunto de documentação online do Python 3. (BARRY, 2015) </small>

<p align="justify">
Este é um editor padrão do Python porém você também
poderá escrever os programas em um editor de sua preferência,
para este livro, por motivos didáticos será utilizado o próprio
IDLE
</p>

<p align="center">
Figura 3 – Aparência do IDLE no Mac Os
</p>

<p align="center">
<img src="resources/img/fig3.png">
</p>

<p align="center">
Fonte: O autor.
</p>

<p align="center">
Figura – 4 – Aparência do IDLE no Windows.
</p>

<p align="center">
<img src="resources/img/fig4.png">
</p>

<p align="center">
Fonte: O autor.
</p>

<p align="justify">
As Figuras 3 e 4 apresentam a aparência do IDLE no
Sistema Operacional Mac Os e Windows. “Quando você iniciar
o IDLE pela primeira vez, será apresentado ao prompt com 'três
divisas' (>>>) no qual você insere o código e imediatamente a
executa para você, exibindo qualquer resultado produzido na
tela” (BARRY, 2015. p. 4). Outro modo de chamar o Python é
abrir seu Terminal (no Windows é muito conhecido como
prompt ou cmd) e escrever o comando python e se as três
divisas aparecerem significa que o Python está corretamente
instalado no seu computador e você está pronto para escrever
programas de verdade.
</p>

<p align="center">
Figura 5 – Chamar o Python pelo terminal no Mac Os
</p>

<p align="center">
<img src="resources/img/fig5.png">
</p>

<p align="center">
Fonte: O autor.
</p>

<p align="center">
Figura 6 – Chamando Python no terminal Windows
</p>

<p align="center">
<img src="resources/img/fig6.png">
</p>

<p align="center">
Fonte: O autor.
</p>

<p align="justify">
Uma observação importante é que, caso sua máquina já
possua outras versões do Python instalada (como no MacOs e
Linux onde o Python 2 já vem instalado por padrão) o
comando necessário para chamar o Python pelo Terminal pode
vir a ser diferente, dentre alguns exemplos estão <b>python,
python3, py, python3.3, python3.5 </b> (ou a versão específica
que você instalou). Agora que você já sabe o que são
algoritmos e já tem o Python 3 instalado no seu computador
podemos dar continuidade ao nosso estudo da Lógica de
Programação.
</p>

Os algoritmos em Python apresentados nesta obra
poderão ser encontrados através [deste link](https://github.com/brunolcarli/AlgoritmosELogicaDeProgramacaoComPython).


# Capítulo 2

## Construindo algoritmos com Python

<p align="justify">
Antes de efetivamente construir nossos algoritmos é
importante sabermos como elaborar um algoritmo. Ascencio e Campos (2010, p. 3) definem um método para construção de algoritmos, sendo estruturado a partir de alguns elementos básicos, dentre eles:
</p>

1. Compreender o problema a ser resolvido;
2. Definir os dados de entrada que deverão ser fornecidos;
3. Definir o processamento, quais operações deverão ser executadas sobre os dados;
4. Definir a saída final, exibindo o resultado obtido através do processamento dos dados;
5. Construir o algoritmo;
6. Testar o algoritmo através de simulações;

<p align="justify">
Vamos realizar cada uma destas etapas e comparar o
último exemplo de algoritmo fornecido (soma de dois
números) em Pseudocódigo e Python para ter uma boa visão de como seria um algoritmo implementado em Python 3:
<p>

1. **Problema a ser resolvido**: Somar dois números;
2. **Dados de entrada**: numero1 e numero2;
3. **Processamento**: Somar o numero1 com o numero2;
4. **Saída**: Exibir o resultado da soma;
5. **Construção do algoritmo**:

| Pseudocódigo | Python |
| ------------ | ------ |
| ALGORITMO: soma | |
| VAR num1,num2,soma:inteiro | |
| INICIO | |
| LEIA(num1) | num1 = input("Insira o primeiro numero ") | 
| LEIA(num2) | num2 = input("Insira o segundo numero ")|
|soma ← num1 + num2 | soma = int(num1) + int(num2)|
| ESCREVA(soma) | print("Resultado: ", soma)|
| FIM. | |

<p align="justify">
Perceba de acordo com a tabela acima que algumas declarações feitas em pseudocódigo não são necessárias em Python.
</p>

<p align="justify">
Para testar o algoritmo abra seu IDLE e selecione na
parte superior a opção <i>File</i> então <i>New File</i>, uma nova janela se abrirá para que você possa escrever o algoritmo, escreva o algoritmo Python apresentado (recomenda-se fortemente que você <b>escreva</b> os comandos ao invés de copiar e colar) então selecione a opção <i>Run</i> e então <i>Run Module</i> na caixa de ferramentas na parte superior da tela, ao executar o algoritmo no IDLE será solicitado que você salve seu programa, então selecione um diretório de sua preferência e salve o arquivo com a extensão .py (uma sugestão é que salve este primeiro algoritmo como soma.py). Após salvar o arquivo, o Python irá executar seu algoritmo e se tudo ocorrer bem sua saída deve ser
parecida com a da Figura 7:
</p>

<p align="center">
Figura 7 – Saída do algoritmo soma.py
</p>

<p align="center">
<img src="resources/img/fig7.png">
</p>

<p align="center">
Fonte: O autor.
</p>

<p align="justify">
Agora vamos entender os comandos utilizados nesse
algoritmo Python, primeiro criamos uma variável num1 (vamos ver mais sobre variáveis adiante) e atribuímos a ela o valor de entrada recebido em input(). O comando input() em Python 3 permite que o usuário entre com um valor que será tratado como string (veremos mais sobre tipos de dados adiante), este comando também permite que um texto seja passado como argumento e exibido na tela, neste caso passamos o texto “Insira o primeiro numero ” como argumento. Quando o interpretador Python ler esta instrução ele vai primeiro exibir o texto ao usuário e ficará aguardando uma entrada, logo que o usuário do sistema fornecer um valor de entrada e confirmar, o interpretador executará a próxima instrução do algoritmo, que será, neste caso, a atribuição de mais um valor de entrada para a variável num2, da mesma forma como fizemos na primeira instrução.
</p>

<p align="justify">
A terceira instrução do algoritmo soma.py irá realizar a operação de processamento que soma num1 e num2 e armazena seu resultado em uma variável chamada soma, para isto utilizamos um método chamado int() que irá dizer ao interpretador Python que durante este processamento as variáveis num1 e num2 devem ser tratadas como números inteiros<sup><small>1</small></sup>.
</p>

<p align="justify">
Por fim a instrução print() diz ao Python para escrever na tela, este é um comando de saída de dados, e exibirá na tela os argumentos que forem fornecido à instrução print(). Neste caso fornecemos um argumento em forma de texto dizendo “O resultado da soma e ” e adicionamos uma vírgula (,) para separar o próximo argumento que foi a variável soma, desta forma o comando de saída exibirá o texto fornecido e o valor guardado na variável soma.
</p>

<hr>
<p align="justify">
<sup><small>1</small></sup> : 
<small>Uma observação importante é que, em Python 3 o comando input( ) vai receber sempre os
dados em formato de cadeia de caracteres (string), sendo tratada como um texto, por este
motivo a necessidade de converter para números os valores isneridos através da instrucão
int( ), em Python 2 o comando input( ) receberia apenas valores numéricos e caso o
usuário entrasse com uma letra ou simbolo o Python retornaria um erro. Em python 2 há
um comando específico para receber entradas de texto chamado raw_input( ). Não se
preocupe com isso por enquanto, mais para frente quando você estiver mais familiarizado
com os tipos de dados isto se tornará mais simples de compreender.</small>
</p>

<hr>

<br />

## Variáveis e tipos de dados

<p align="justify">
Variáveis em Algoritmos e Lógica de Programação são
valores que podem sofrer alterações no decorrer do algoritmo. Ascencio e Campos (2010, p. 7) afirma que “Um algoritmo e, posteriormente, um programa, recebem dados, que precisam ser armazenados no computador para serem posteriormente utilizados no processamento. Esse armazenamento é feito na
memória”, logo, sempre que declaramos uma variável em
nosso algoritmo o computador irá separar um espaço na
memória para que um dado possa ser armazenado ali. Segundo Ascencio e Campos(Op. Cit) uma variável “possui nome e tipo, e seu conteúdo pode variar ao longo do tempo, durante a execução de um programa. Embora uma variável possa assumir diferentes valores, ela só pode armazenar um valor a cada instante”.
</p>

<p align="justify">
Agora vamos fazer uma pequena abstração, imagine um
garoto chamado Pedrinho. Pedrinho possui uma variável
chamada idade que neste exato momento possui o valor 7, representando que Pedrinho tem 7 anos. No seu próximo aniversário Pedrinho completará mais um ano de vida então o valor da sua variável idade será incrementado em um, passando agora a representar o valor 8. Esta pequena analogia demonstra a mutabilidade dos valores guardados em uma variável, que recebe este nome justamente por seus valores variarem ao longo de um algoritmo.
</p>

<p align="justify">
As variáveis sempre guardam valores de um respectivo
tipo de dado, que de acordo com Ascencio e Campos (2010, p.8) os mais comuns são numéricos, lógicos e literais.
</p>

*Numéricos*

<p align="justify">
Os dados do tipo numérico são divididos em duas
categorias: Inteiros e Reais. “Os números inteiros podem ser positivos ou negativos e não possuem parte
fracionária”(ASCENCIO; CAMPOS, 2010), como exemplo de
números inteiros temos:
</p>

<p align="center">
12, -7, 154, 0, -98
</p>

<p align="justify">
Os números Reais são aqueles que possuem uma parte
fracionária e podem ser positivos ou negativos, como por exemplo:
</p>

<p align="center">
3.14, 2.9876, -1.98,  0.765
</p>

<p align="justify">
Uma observação importante deixada por Ascencio e
Campos (2010) é que “os números reais seguem a notação da língua inglesa, ou seja, a parte decimal é separada da parte inteira por um . (ponto) e não por uma , (vírgula)” é importante compreender isso desde o início pois poderá evitar complicações futuras quando implementar seu algoritmo.
</p>

<br />

*Lógicos*

<p align="justify">
Os valores lógicos, também chamados de booleanos
(ASCENCIO; CAMPOS, 2010), somente podem assumir dois
valores: verdadeiro ou falso. Estes são utilizados muitas vezes em comparações lógicas e verificações condicionais (veremos mais sobre isto nos próximos capítulos).
</p>


<br />

*Literais*

<p align="jutify">
Os dados do tipo literal são formados por sequências de caracteres (letras maiúsculas, minúsculas e símbolos) ou por um único caractere(ASCENCIO; CAMPOS, 2010). Este tipo de dado é popularmente chamado de string, sendo representado pelo texto envolto por “aspas”, como no exemplo a seguir:
</p>

<p align="center"> “aluno” </p>
<p align="center"> “Carro”</p>
<p align="center"> “Minha casa é azul”</p>
<p align="center"> “fulano@email.com”</p>
<p align="center"> “12 x 10 =”</p>
<p align="center"> “F$0c!3^y</p>

<p align="justify">
Perceba que mesmo os numerais que estiverem entre
aspas serão identificados como dados literais, e Puga e Rissetti (2010, p. 37) afirmam que “Os números armazenados em uma variável cujo tipo de dado é literal não poderão ser utilizadas
para cálculo”, somente sendo possível realizar operações matemáticas com as variáveis do tipo numérico, desta forma é importante conhecer os tipos de dados que estamos trabalhando.
</p>

><small>Definir o tipo de dado mais adequado para ser armazenado em uma variável é uma questão de grande importância para garantir a resolução do problema. Ao desenvolver um algoritmo, é necessário que se tenha conhecimento prévio do tipo de informação (dado) que será utilizado para resolver o problema proposto. Daí, escolhe-se o tipo adequado para a variável que representa esse valor. (PUGA; RISSETTI, 2010, p. 36)</small>

<p align="justify">
As variáveis também possuem identificadores, que nada
mais são do que o seu próprio nome. Sempre que definimos
uma variável a declaramos com um nome, este nome chama-se
identificador, praticamente todos os comandos possuem
identificadores, o print( ) é um identificador para uma rotina
de exibição de dados por exemplo.
</p>

<p align="justify">
É importante saber que existem algumas regras para
formação dos identificadores, segundo Ascencio e
Campos(2010, p. 9), sendo elas:
</p>

+ Somente podem ser utilizadas letras maiúsculas,
minúsculas, números e o caracter sublinhado ( _ ) no
nome das variáveis;

+ O caractere inicial deve obrigatoriamente ser uma letraou o caractere sublinhado, não se deve começar o nome da variável por números;

+ Não são permitidos espaços em branco nem caracteres especiais (!@#$%^&*+-<>=...) com exceção do
sublinhado ( _ );

+ Não podemos utilizar palavras reservadas, estas são
nomes iguais a outros identificadores como comandos
da linguagem de programação que você estiver
utilizando, nomes de variáveis já declaradas no escopo, etc.

<p align="center">
Tabela 3 – Identificadores válidos e inválidos
</p>

| FORMA VALIDA | Razão | FORMA INVÁLIDA | Razão |
| ------------ | ----- | -------------- | ----- |
| Joao12 | Começa com letras | 8C | Não pode começar com números|
| cpf | Contém somente letras | nome usuario | Não pode conter espaços em branco|
| _nome | Pode começar com *underscore* (_)| True | Não pode conter nomes de palavras reservadas da linguagem (True é uma palavra reservada para um tipo de dado booleano) |
| registro_usuario | Liga duas palavras através de um *underscore* | id-paciente | Não pode conter careacteres especiais (- é um careactere que representa a subtração) |
| NOTA | Caixa alta é permitido | bot@ao | Não é permitido o uso de carácteres especiais (exceto o underscore) |

<p align="center">Fonte: O autor.</p>

<br />

## Variáveis em Python

<p align="justify">
As variáveis em Python são bem flexíveis, se adaptando
ao tipo de dado e alocando espaço dinamicamente na memória. Para atribuir um valor à uma variável utilizamos o operador de atribuição, representado pelo careactere <b>=</b>
</p>

    nome = "Edgar Morin"
    idade = 97
    peso = 67.24

<p align="center">
Diferentemente do pseudocódigo e de algumas
linguagens de programação não precisamos declarar o tipo de variável para que o Python a reconheça. Vamos a um exemplo, abra seu IDLE e crie um novo arquivo (<i>File</i> então <i>New File</i>), insira o pequeno trecho a seguir:
</p>

    mensagem = "Ola Mundo"
    print(mensagem)

Salve seu arquivo e execute em <i>run module</i>. Sua saída deve ser parecida com esta:

<p align="center">
<img src="resources/img/fig_exemplo1.png">
</p>

<p align="justify">
Tome cuidado ao escrever o identificador da variável,
pois o Python diferencia letras maiúsculas e minúsculas, assim a variável <b>Carro</b> é diferente de <b>carro</b>. Da mesma forma, caso o identificador esteja escrito incorretamente, nosso interpretador
retornará um erro. Tente reescrever o programa anterior omitindo uma letra da variável mensagem na instrução print( ), desta forma:
</p>

    mensagem = "Ola Mundo"
    print(mesagem)

<p align="justify">
Perceba que criamos uma variável chamada mensagem,
mas passamos para a instrução print() um identificador chamado <b>mesagem</b>. O interpretador Python irá retornar um erro parecido com este:
</p>

<p align="center">
<img src="resources/img/fig_exemplo2.png">
</p>

<p align="justify">
Não se preocupe com os erros, eles irão aparecer muitas vezes nas suas simulações de algoritmo. O Python é muito eficiente ao informar para o programador onde está o erro e que tipo de erro foi encontrado. Veja, na primeira linha temos
um <i>Traceback</i>, que segundo Matthes(2016, p. 52) “um traceback é um registro do ponto em que o interpretador se deparou com problemas quando tentou executar seu código”. 
</p>

<p align="justify">
Na próxima linha, o interpretador indica qual foi o arquivo e a linha do arquivo em que o programa parou. Neste caso vemos que o arquivo <b>exemplo1.py</b> possui um erro na linha 2. 
</p>

<p align="justify">
A terceira linha tenta nos mostrar aproximadamente a instrução onde o Python encontrou o erro, que foi na instrução <i>print(mesage)</i>.
</p>

<p align="justify">
Por fim, na quarta linha da mensagem de erro temos o tipo de erro encontrado, que neste caso é um <i>NameError</i> que é um erro comum gerado quando tentamos operar um identificador não existente. Como não declaramos nenhuma variável chamada <b>mesagem</b> o interpretador retornou um erro avisando <strike>(em trocadilhos)</strike> <i>“Olha Sr. Programador, o sr. me pediu para escrever o conteúdo identificado por 'mesagem' mas eu não encontrei nada na memória com esse identificador, tem certeza que é isso mesmo?”</i>. Se o Python pudesse falar ele
diria algo como isto, mas as informações que ele mostra já são suficientes pra nos informar onde foi que erramos<sup><small>2</small></sup>.
</p>

<hr>
<sup><small>2</small></sup> : 
<small>No Python você verá que os erros são chamados de exceptions, a maioria deles estão listados na
<a href="https://docs.python.org/2/library/exceptions.html">documentação oficial do Python</a></small>
<hr>

<p align="justify">
Ao declarar uma variável em Python, também devemos respeitar as palavras reservadas da linguagem, ou seja os identificadores já existentes. Segundo a documentação do Python temos dispostos alguns exemplos de palavras reservadas (<i>keywords</i>):
</p>

<p align="center">
Figura 8 – Palavras reservadas em Python:
</p>

<p align="center">
<img src="resources/img/fig8.png">
</p>

<p align="center">
Fonte: https://docs.python.org/3.5/reference/lexical_analysis.html#identifiers
</p>

<br />

Vamos exercitar mais um pouco e criar uma variável
para cada tipo de dado que acabamos de conhecer:

    texto = "mensagem com texto"
    numero_inteiro = 9
    fracionario = 1.29
    dado_logico = True

    print(texto, numero_inteiro, fracionario, dado_logico)

<p align="justify">
Os dados do tipo literal em Python podem ser
declarados entre 'aspas simples' ou “aspas duplas”, desde que se abra e feche as mesmas aspas, não sendo possível abrir um aspa simples e fechar com uma dupla ('exemplo”) e nem ao contrário (“exemplo'), mas pode-se abrir uma aspa simples dentro de uma aspa dupla e vice-versa (“Assim 'por exemplo'”, ou ainda, 'Assim “por exemplo”'). “Python chama qualquer número com um ponto decimal de número de ponto flutuante (float). Esse termo é usado na maioria das linguagens de programação e refere-se ao fato de um ponto decimal poder aparecer em qualquer posição de um número” (MATTHES, 2016, p. 63), ressalta-se aqui a importância de declarar os números reais (<i>float</i>) utilizando-se o ponto ( . ) para representar a parte fracionária e não a virgula ( , ) do contrário o Python irá
retornar um erro.
</p>

<p align="justify">
Os dados lógicos ou booleanos devem ser declarados
com a primeira letra maiúscula (<b>True</b> ou <b>False</b>), se você inserir o valor true, ou inserir o valor false, o Python não irá reconhecer e irá enviar um traceback indicando um <i>NameError</i> como vimos anteriormente, sua desculpa é que nenhum identificador com o nome 'true' ou 'false' foi definido, isto porque assim como muitas outras linguagens, o Python é Case Sensitive, o que significa que ele diferencia letras
maiúsculas e minúsculas, logo, True e true são duas coisas completamente distintas para nosso interpretador, sempre que escrevermos um algoritmo devemos ser muito claros e específicos.
</p>

<p align="justify">
Podemos passar as variáveis separadas por vírgula para
a instrução print( ) como no exemplo anterior, ou podemos fazer uma instrução para cada variável:
</p>

    print(texto)
    print(numero_inteiro)
    print(fracionario)
    print(dado_logico)


<p align="justify">
Há outras formas de imprimir na tela pulando linhas, e formas mais eficientes de se trabalhar com os dados de forma que o desempenho do algoritmo seja superior, porém em nível de aprendizado estas instruções demonstram muito bem o comportamento do interpretador Python.
</p>

<p align="justify">
Vimos no inicio deste capítulo que uma variável
somente pode guardar um valor por vez, isso quer dizer que se eu declarar uma variável chamada surpresa e atribuir diferentes valores para ela, cada vez que um novo valor for atribuído, o
anterior será esquecido, veja:
</p>

    surpresa = 9
    surpresa = 16.78
    surpresa = 'doce de goiaba'
    surpresa = "CWB City Rocks"

    print(surpresa)

<p align="justify">
Atribuímos inicialmente o o valor inteiro 9 para a
variável surpresa, então logo em seguida atribuímos o valor real 16.78, então a próxima instrução diz ao Python para atribuir uma string à mesma variável, e em seguida pede para atribuir outra string. No final dizemos ao Python para escrever
o valor da variável surpresa.
</p>

<p align="center">
<img src="resources/img/fig_exemplo3.png">
</p>

<p align="justify">
O valor exibido na tela foi o último valor a ser atribuído à variável, todos os outros valores foram desconsiderados, isso porque uma variável somente pode guardar um valor de cada
vez. Esta sequência de instruções também demonstra como o Python consegue atribuir diferentes tipos de dados em uma mesma variável, o que não aconteceria em muitas outras linguagens de programação.
</p>

<p align="justify">
Lembra-se do algoritmo soma.py que construímos no
início do capítulo? Neste algoritmo o a instrução input( ) irá esperar o usuário entrar com um tipo de dado, porém independente do tipo de dado fornecido, o Python irá armazenar a entrada como uma string (dado do tipo literal), então para realizar a soma tivemos que fazer uma conversão utilizando uma instrução int( ). Quando passamos um tipo de dado para a instrução int( ) o Python tentará realizar uma conversão do tipo de dado fornecido para um tipo inteiro. Vamos ver um exemplo:
</p>

    numero = '12'
    print(numero)
    numero = int(numero)
    print(numero)

<p align="justify">
Primeiro declaramos uma variável chamada numero e
pedimos para mostrá-la na tela, então realizamos a conversão para inteiro e pedimos para mostrar na tela. Na saída não conseguimos identificar a diferença, observe o resultado:
</p>

<p align="center">
<img src="resources/img/fig_exemplo4.png">
</p>

<p align="justify">
Mas se tentarmos realizar uma operação matemática,
como a soma, em variáveis do tipo literal o que acontece é um evento chamado concatenação, e não a adição em si, veja o exemplo:
</p>

    numero = '12'
    numero2 = '3'
    print(numero + numero2)

    numero = int(numero)
    numero2 = int(numero2)
    print(numero + numero2)

<p align="justify">
Primeiro declaramos duas strings e tentamos exibir a
soma de ambas, depois convertemos as strings para inteiro e exibimos a soma das variáveis:
</p>

<p align="center">
<img src="resources/img/fig_exemplo5.png">
</p>

<p align="justify">
Observe os resultados, na primeira linha obtivemos o
resultado da concatenação, que nada mais é do que juntar a segunda string ao final da primeira, resultando não na soma, mas na junção das duas variáveis literais em um único texto. Ja no segundo resultado pudemos obter o resultado da operação de adição, pois a instrução int() converteu os dados literais para numéricos e o Python compreendeu que deveria realizar uma operação aritmética com estes dados.
</p>

<p align="justify">
Mas o que aconteceria se você tentasse converter uma
letra para número?
</p>

    fruta = "banana"
    banana = int(fruta)
    print(fruta)

<p align="justify">
Ao criarmos uma variável literal com caracteres não
numéricos e forçarmos uma conversão, o Python logo retornará um erro, pois não é possível converter letras para números, o mesmo aconteceria se tentássemos converter um dado do tipo
real ou lógico.
</p>

<p align="center">
<img src="resources/img/fig_exemplo6.png">
</p>

<p align="justify">
O erro retornado é um ValueError, dizendo que
os valores expressados na tentativa de execução não são válidos, por isto devemos tomar muito cuidado ao trabalhar com os tipos de dados para não levantar erros inesperados.
</p>

<p align="justify">
Caso você tenha dúvida quanto ao tipo de dado que
você está lidando, o Python tem a instrução type( ). Quando você passar uma variável para a instrução type(variavel) ele ira informar o tipo de dado dessa variável, como no exemplo a seguir:
</p>

    fruta = "banana"
    numero = 78
    God = False
    PI = 3.1415

    print(type(fruta))
    print(type(numero))
    print(type(God))
    print(type(PI))

Saida:

<p align="center">
<img src="resources/img/fig_exemplo7.png">
</p>

<p align="justify">
Vemos que que cada tipo de dado pertence a uma classe
que representa um tipo de dado específico: Literal (str), Inteiro (int), Lógico (bool) e Real (float).<sup><small>3</small></sup>
</p>

<hr>
<sup><small>3</small></sup> : 
<small>O Python também tem o tipos de dados complex, mas não será abordado
nesta obra, você pode conferir o modelo de dados do Python <a href="https://docs.python.org/3/reference/datamodel.html#">aqui.</a></small>
<hr>

<br />

## Constantes

<p align="justify">
Da mesma forma que possuímos valores variáveis,
também temos valores constantes, ou seja, que não se
modificam ao longo do seu algoritmo. No Python, por questões de boas práticas, sempre definimos uma constante com todas as letras do identificador em CAIXA ALTA, ou seja, letras maiúsculas, dessa forma:
</p>

    PI = 3.1215
    ALTURA = 600
    LARGURA = 600

<p align="justify">
Porém escrever uma variável em caixa alta não a torna realmente uma "constante", o que quer dizer que ainda se pode modificar o valor desta variável atribuindo outro valor à mesma. Escrever com letras maiúsculas é apenas uma boa prática para facilitar a legibilidade do código e distinção das variáveis pelo programador. Em Python é muito comum declarar valores constantes em formas de tuplas, que nada mais são que listas imutáveis, o que torna a alteração do valor contido na variável impossível de ser realizado.
</p>

Declarando uma tupla:

    quantidade = (100)

Para acessar o valor da tupla:

    qt = quantidade[0]
    print(qt)

Não se preocupe quanto a isto neste momento, veremos mais sobre tuplas em seções futuras deste livro.

## Expressões

<p align="justify">
Quando estivermos elaborando nossos algoritmos,
muitas vezes teremos que utilizar expressões aritméticas para
processar os dados, as expressões são formadas por operadores
aritméticos e possuem, assim como na matemática, uma
prioridade de execução, denominada precedência. Segue um
quadro com os operadores em Python:
</p>

<p align="center">
Tabela 4 – Operadores aritméticos mais comuns em Python e sua
precedência
</p>

| OPERADOR | OPERAÇÃO | PRECEDÊNCIA | DESCRIÇÃO |
| :------: | :------: | :---------: | --------- |
| + | Adição | 0 | Realiza a soma dos operandos. Ex: a + b |
| - | Subtração | 0 | Realiza a subtração dos operandos. Ex: total - desconto |
| / | Divisão | 1 | Realiza a divisão dos operandos. Ex: 12 / 2 |
| // | Divisão inteira | 1 | Retorna a parte inteira da divisão. Ex: 3 // 2 (resulta em 1) |
| * | Multiplicação | 1 | Multiplica os operandos. Ex: 2 * 5 |
| ** | Exponenciação | 2 | Eleva o operando a esquerda pelo operando a direita. Ex: 5**2 (cinco ao quadrado) |
| % | Módulo | 2 | Obtém o resto da divisão dos operandos. Ex: 7%2 (Resulta em 1) |


<p align="justify">
As operações com menor precedência são executadas
por último, neste caso ao observar a expressão 2 + 3 * 5, assim como na matemática, a primeira operação a ser realizada é a multiplicação (3 * 5), somente então a adição será realizada (2 + 15). Estas precedências podem ser alteradas fazendo uso do
parêntese ( ), dando precedência para a expressão que estiver dentro do parêntese, desta forma:
</p>

    a = 2 + 3 * 5
    b = (2 + 3) * 5

    print("O valor de a: ", a)
    print("O valor de b: ", b)

Saída:

<p align="center">
<img src="resources/img/fig_exemplo8.png">
</p>

Nós também temos os operadores relacionais, que
permitem realizar comparações entre valores:

<p align="center">
Tabela 5 – Operadores relacionais em Python
</p>

| OPERADOR | COMPARAÇÃO | DESCRIÇÃO |
| :------: | :--------: | --------- |
| == | Igualdade | Dois sinais de = compara se dois valores são idênticos. Ex: a == b | 
| != | Diferença | Compara se dois valores são diferentes. Ex: a != b |
| > | Maior | Compara se o primeiro valor é maior que segundo. Ex: a > b |
| < | Menor | Compara se o primeiro valor é menor que o segundo. Ex: a < b |
| >= | Maior igual | Compara se o primeiro valor é maior ou igual ao segundo valor. Ex: a >= b |
| <= | Menor igual | Compara se o primeiro valor é menor ou igual ao segundo. Ex: a <= b |

<p align="center">Fonte: O autor.</p>

As expressões relacionais sempre retornarão um valor
lógico (**True** ou **False**), veja no exemplo a seguir:

    a = 2
    b = 3

    print(a == b)
    print(a != b)
    print(a > b)
    print(a < b)
    print(a >= a)
    print(a <= b)

Saída:

<p align="center">
<img src="resources/img/fig_exemplo9.png">
</p>

<p align="justify">
Existem mais operadores que não cobriremos aqui, mas
você pode conferir a lista completa na documentação do Python.<small><sup>4</sup></small>
</p>

<p align="justify">
Uma aplicação interessante em Python é a multiplicação de strings, veja:
</p>

    chaves = "pi"
    print(chaves * 10)

Saída:

<p align="center">
<img src="resources/img/fig_exemplo10.png">
</p>

<p align="justify">
Temos também os operadores lógicos que podem ser
utilizados juntamente com os relacionais fazendo comparações, a seguir os operadores lógicos:
</p>

<p align="center">
Tabela 6 – Operadores lógicos em Python
</p>

| OPERADOR | OPERAÇÃO | PRECEDÊNCIA | DESCRIÇÃO |
| :------: | :------: | :---------: | --------- |
| or | Disjunção | 1 | A disjunção entre duas operações resultara verdadeiro se um dos valores for verdadeiro |
| and | Conjunção | 2 | A conjunção resultará em verdadeiro se, e somente se, todos os valores examinados forem verdadeiros |
| not | Negação | 3 | A negação inverte o valor lógico da variável examinada. Se o valor for verdadeiro ele se tornará falso, e vice-versa. |

<p alig="center">Fonte: O autor </p>

Vamos examinar estas operações com o Python:

    a = 2
    b = 3
    c = 4

    print(a > b or a > c)
    print(a < b and a < c)
    print(not a == b)

Saída:

<p align="center">
<img src="resources/img/fig_exemplo11.png">
</p>

<p align="justify">
Veja que definimos as variáveis a = 2, b = 3 e c =4.
Então fizemos um pergunta ao Python como que “Python, a é maior que b OU a é maior que c?” então na primeira linha da saída temos a resposta False, pois a não é nem maior que b e nem maior que c, a na disjunção somente obtemos uma saída verdadeira se pelo menos uma expressão resultar em verdadeiro, como nossas duas expressões resultaram falso, a disjunção resultou falso.
</p>

<p align="justify">
Então perguntamos ao Python: “a é menor que b E a é
menor que c?”, o Python responde: True, pois na conjunção obtemos resultado verdadeiro se todas as expressões resultarem verdadeiro, como 2 é menor que 3 e também é menor que 4, nossa avaliação lógica retornou verdadeiro.
</p>

<p align="justify">
Por fim perguntamos ao Python se a e b são idênticos e informar o valor lógico inverso (como assim? você pergunta), temos que 2 não é igual a 5, então o resultado da avaliação seria Falso, mas como dissemos ao Python para nos informar o inverso ele respondeu Verdadeiro (True). Um detalhe interessante é que sempre que uma variável estiver inicializada com o valor 0 ela retornará Falso.
</p>

## Funções Intrínsecas