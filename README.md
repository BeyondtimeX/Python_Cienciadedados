# Python para Ciencia de Dados ![python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

#### Ambiente de Desenvolvimento e Primeiros Passos com Python

Python nasceu em 1989 como um hobby, do programador Guido Van Rossum. A ideia inicial era dar continuidade a linguagem ABC, que era desenvolvida no Centro de Pesquisa Holandês (CWI).

Python foi influenciada por ABC, que era uma linguagem pensada para iniciantes, devido a sua facilidade de aprendizagem e utilização.
Os objetivos de Van Rossum para a linguagem Python eram:

* Uma linguagem fácil e intuitiva.
* Código aberto, para que todos possam contribuir.
* Código tão inteligível quanto Inglês.
* Adequada para tarefas diárias, e produtiva!

Guido Van Rossum inicia o desenvolvimento em 1989 e em fevereiro de 1991 é lançada a primeira versão pública: 0.9.0.

Em 1995 Guido lança a versão 1.2, enquanto trabalhava no CWI. Com o vínculo encerrado com o centro de pesquisa, Van Rossum e a equipe principal de desenvolvedores Python mudaram-se para BeOpen.com, nasce a BeOpen Python Labs.

A segunda versão do Python é publicada em Outubro de 2000, nessa versão nasce List Comprehensions e uma melhoria no coletor de lixo para remoção de referências cíclicas.

Em 2001 nasce a Python Software Foundation (PSF), que a partir do Python 2.1 possui todo o código, documentação e especificações da linguagem.

Em 2008 é lançada a versão 3.0, que resolveu muitos problemas de design da linguagem e melhorou a performance. Algumas mudanças foram muito profundas e dessa forma a versão 3.x não é retrocompatível.

Atualmente estamos na versão 3.10.2 do Python.

Python é uma linguagem muito versátil!

* Tipagem dinâmica e forte.
* Multiplataforma e multiparadigma.
* Comunidade gigante e ativa.
* Curva de aprendizado baixa.

---------------------------------------
###### Windows

Como a maioria dos programas Windows, o Python possui um instalador que pode ser baixado acessando: http://www.python.org. Após executar a download, faça a instalação seguindo os passos descritos no tutorial: https://python.org.br/instalacao-windows/.


Baixar e configurar a IDE

VSCode ou PyCharm

VSCode é uma ótima ferramenta e será a nossa escolha por alguns motivos:

*Gratuita.
*Suporta múltiplas tecnologias.
*Boa performance.
* Acesse o site: https://code.visualstudio.com/.

---------------------------------------
###### Criando nosso primeiro programa

Programar consiste em informar ao computador uma sequência de rotinas que devem ser processadas. Imagine uma receita de bolo, precisamos saber os ingredientes e modo de preparo. Seguindo corretamente as instruções ao fim do processo teremos um bolo.

Criando nosso arquivo

Para criar a nossa receita de bolo em Python, precisamos criar um arquivo com extensão py. Com o arquivo criado podemos inserir nossos ingredientes e modo de preparo!

![image](https://user-images.githubusercontent.com/88558377/190122195-db300619-bb07-4ec4-b797-32cf16e7a197.png)

---------------------------------------
######  Tipos de dados

###### Objetivo geral

* Conhecer os tipos de dados em Python.

O que são tipos?

// Espaço alocado e operações

Por que usamos tipos?

Os tipos servem para definir as caracteristicas e comportamentos de um valor (objeto) para o interpretador. Por exemplo:

* Com esse tipo eu sou capaz de realizar operações matemáticas.
 Esse tipo para ser armazenado em memória irá consumir 24 bytes.

###### Tipos em Python

Os tipos built-in são:

![image](https://user-images.githubusercontent.com/88558377/190117398-acba02c1-2c45-4c8b-8c2c-7112a162ddfb.png)

###### Números inteiros

* Números inteiros são representados pela classe int e possuem precisão ilimitada. São exemplos válidos de números inteiros:
1, 10, 100, -1, -10, -100…99001823

###### Números de ponto flutuante

* Os números de ponto flutuante são usados para representar os números racionais e sua implementação é feita pela classe **float**. São exemplos válidos de números de ponto flutuante:

* 1.5, -10.543, 0.76…999278.002

###### Booleano

É usado para representar verdadeiro ou falso, e é implementado pela classe **bool**. Em Python o tipo booleano é uma subclasse de int, uma vez que qualquer número diferente de 0 representa verdadeiro e 0 representa falso. São exemplos válidos de booleanos:

**True** e *False**

###### Strings

* Strings ou cadeia de caracteres são usadas para representar valores alfanúmericos, em Python as strings são definidas utilizando a classe **str**. São exemplos válidos de string:

* "Python", 'Python', """Python""", '''Python''', "p"

**https://docs.python.org/3/library/stdtypes.html**

![image](https://user-images.githubusercontent.com/88558377/190120884-4267be43-3413-4b94-893d-a01fab58de9a.png)

---------------------------------------
###### Modo interativo

Como usar o modo interativo do interpretador Python

O interpretador Python pode executar em modo que possibilite o desenvolvedor a escrever código, e ver o resultado na hora.

###### niciando o modo interativo

* Existem duas formas de iniciar o modo interativo, chamando apenas o interpretador (python) ou executando o script com a flag -i (python -i app.py).

###### Funções dir e help

// Documentação offline e direto no terminal

###### dir

Sem argumentos, retorna a lista de nomes no escopo local atual. Com um argumento, retorna uma lista de atributos válidos para o objeto. Exemplo:
* dir()
* dir(100)

###### help

Invoca o sistema de ajuda integrado. É possível fazer buscas em modo interativo ou informar por parâmetro qual o nome do módulo, função, classe, método ou variável. Exemplo:
* help()
* help(100)

**https://wiki.python.org.br/ModoInterativo**

---------------------------------------
###### Variáveis e constantes

###### Variáveis

* Em linguagens de programação podemos definir valores que podem sofrer alterações no decorrer da execução do programa. Esses valores recebem o nome de variáveis, pois eles nascem com um valor e não necessariamente devem permanecer com o mesmo durante a execução do programa.

![image](https://user-images.githubusercontent.com/88558377/190127236-2f91d80b-f493-4fe3-bce0-2415f8dd92c9.png)

![image](https://user-images.githubusercontent.com/88558377/190127350-1cd3b543-a965-4508-8897-6e9d6a2ba73d.png)


###### Alterando os valores

* Perceba que não precisamos definir o tipo de dados da variável, o Python faz isso automaticamente para nós. Por isso não podemos simplesmente criar uma variável sem atribuir um valor. Para alterar o valor da variável basta fazer uma atribuição de um novo valor:

![image](https://user-images.githubusercontent.com/88558377/190128243-7e9d0423-f200-4e7c-b039-eeb54d9347d0.png)

![image](https://user-images.githubusercontent.com/88558377/190128368-6b303558-e0b4-4d04-a3e8-70e7512b0849.png)


 ###### Constantes

* Assim como as variáveis, constantes são utilizadas para armazenar valores. Uma constante nasce com um valor e permanece com ele até o final da execução do programa, ou seja, o valor é imutável.

###### Python não tem constantes

* Não existe uma palavra reservada para informar ao interpretador que o valor é constante. Em algumas linguagens por exemplo: Java e C utilizamos final e const, respectivamente para declarar uma constante.
Em Python usamos a convenção que diz ao programador  que a variável é uma constante. Para fazer isso, você deve criar a variável com o nome todo em letras maíusculas:

![image](https://user-images.githubusercontent.com/88558377/190129375-0352d358-f4f8-48dd-8811-d31ddc2c5bd0.png)

###### Boas práticas

// Seguindo as convenções

* O padrão de nomes deve ser snake case.
* Escolher nomes sugestivos.
* Nome de constantes todo em maiúsculo.

---------------------------------------
###### Conversão de tipos

###### Convertendo tipos

Em alguns momentos é necessário será necessário converter o tipo de uma variável para manipular de forma diferente. Por exemplo:

* Variáveis do tipo string, que armazenam números e precisamos fazer alguma operação matemática com esse valor.

* Inteiro para float

![image](https://user-images.githubusercontent.com/88558377/190131856-da542c92-54c0-48d2-baea-cc9a10705b64.png)

###### Float para inteiro

![image](https://user-images.githubusercontent.com/88558377/190132077-115c16e2-3580-4485-a495-4e143ba92237.png)


###### Conversão por divisão

![image](https://user-images.githubusercontent.com/88558377/190132339-6732a7fe-8aea-4a73-bea1-679fda8338fe.png)

###### Numérico para string

![image](https://user-images.githubusercontent.com/88558377/190132630-48cbc509-bbca-468b-9e47-513747cb7474.png)

###### String para número

![image](https://user-images.githubusercontent.com/88558377/190132869-2e5d476d-85cf-4734-a753-802252c8aa72.png)

###### Erro de conversão

![image](https://user-images.githubusercontent.com/88558377/190133132-47ffaa8c-b95d-4b02-be32-bf05e39c6238.png)

---------------------------------------
###### Funções de entrada e saída

Lendo valores com a função input

###### Função input

* A função builtin input é utilizada quando queremos ler dados da entrada padrão (teclado). Ela recebe um argumento do tipo string, que é exibido para o usuário na saída padrão (tela). A função lê a entrada, converte para string e retorna o valor.

###### Exemplo:

![image](https://user-images.githubusercontent.com/88558377/190133482-c420e83d-9c1e-4751-9a62-ef1aa9ee1f1b.png)

###### Função print

* A função builtin print é utilizada quando queremos exibir dados na saída padrão (tela). Ela recebe um argumento obrigatório do tipo varargs de objetos e 4 argumentos opcionais (sep, end, file e flush). Todos os objetos são convertidos para string, separados por sep e terminados por end. A string final é exibida para o usuário.

###### Exemplo:

![image](https://user-images.githubusercontent.com/88558377/190133808-106eaa80-a810-4c74-9411-07cfcac34a81.png)

![image](https://user-images.githubusercontent.com/88558377/190133869-2112ad8a-abbd-4c3d-a498-19d89ddadc0a.png)


**https://docs.python.org/3/library/functions.html#input**

**https://docs.python.org/3/library/functions.html#print**

---------------------------------------
###### Operadores aritméticos

* O que são?

Os operadores aritméticos executam operações matemáticas, como adição, subtração com operandos.

![image](https://user-images.githubusercontent.com/88558377/190137863-ef5afef6-2d13-4032-9a62-0023e0800558.png)

---------------------------------------
###### Precedência de operadores

* Na matemática

Na matemática existe uma regra que indica quais operações devem ser executadas primeiro. Isso é útil pois ao analisar uma expressão, a depender da ordem das operações o valor pode ser diferente:

x = 10 - 5 * 2 
x é igual a 10 ou 0?

A definição indica a seguinte ordem como a correta:

* Parêntesis
* Expoêntes
* Multiplicações e divisões (da esquerda para a direita)
* Somas e subtrações (da esquerda para a direita)

###### Exemplo:

![image](https://user-images.githubusercontent.com/88558377/190138382-ebb148f3-d7e1-45bb-a6c5-f5bdcc150ddf.png)

---------------------------------------
######  Conhecendo os operadores de comparação

O que são?

São operadores utilizados para comparar dois valores.

![image](https://user-images.githubusercontent.com/88558377/190139262-8b7e6947-002e-4324-813f-ee122c47e667.png) ![image](https://user-images.githubusercontent.com/88558377/190139303-bd1bb689-13d5-4a09-b9d6-dd2998755a1e.png)

---------------------------------------
###### Operadores de atribuição

operadores utilizados para definir o valor inicial ou sobrescrever o valor de uma variável.

![image](https://user-images.githubusercontent.com/88558377/190140543-47738c29-7311-4cb9-97db-929113e25780.png) ![image](https://user-images.githubusercontent.com/88558377/190140640-1917caeb-1db1-4416-baf5-252239196a7f.png)

---------------------------------------
###### Operadores Lógicos

O que são?

* São operadores utilizados em conjunto com os operadores de comparação, para montar uma expressão lógica. Quando um operador de comparação é utilizado, o resultado retornado é um booleano, dessa forma podemos combinar operadores de comparação com os operadores lógicos, exemplo:
op_comparacao + op_logico + op_comparacao… N …

![image](https://user-images.githubusercontent.com/88558377/190142028-a97270f7-81c8-4997-a69d-b843c0a13f7b.png)![image](https://user-images.githubusercontent.com/88558377/190142100-e057f444-80e5-4a6b-bbd0-68eb1246c640.png)

---------------------------------------
 ###### Operadores de identidade
 
 **O que são?**
 
 * São operadores utilizados para comparar se os dois objetos testados ocupam a mesma posição na memória.

![image](https://user-images.githubusercontent.com/88558377/190142758-f00ce4aa-345b-4c31-80d6-6103126510fc.png)

---------------------------------------
 ###### Operadores de Associação

**O que são?**

* São operadores utilizados para verificar se um objeto está presente em uma sequência.

![image](https://user-images.githubusercontent.com/88558377/190143228-46775925-3c7d-4446-9597-743ef7c3bacf.png)

---------------------------------------
###### O papel da indentação

**A estética**

* Identar código é uma forma de manter o código fonte mais legível e manutenível. Mas em Python ela exerce um segundo papel, através da indentação o interpretador consegue determinar onde um bloco de comando inicia e onde ele termina.


**Bloco de comando**

* As linguagens de programação costumam utilizar caracteres ou palavras reservadas para terminar o início e fim do bloco. Em Java e C por exemplo, utilizamos chaves:

**Bloco em Java**

![image](https://user-images.githubusercontent.com/88558377/190156615-e7982ad0-a278-4349-a2d1-80701b438002.png)

**Bloco em Java sem formatar**

![image](https://user-images.githubusercontent.com/88558377/190156712-2e62c7cc-31cc-4859-aa4a-c9d2b4d264d2.png)

**Utilizando espaços**

* Existe uma convenção em Python, que define as boas práticas para escrita de código na linguagem. Nesse documento é indicado utilizar 4 espaços em branco por nível de indentação, ou seja, a cada novo bloco adicionamos 4 novos espaços em branco.

![1](https://user-images.githubusercontent.com/88558377/190156835-f827ade8-d3ef-4950-bbdf-c407076c82bf.PNG)


**Isso não funciona em Python!**

![image](https://user-images.githubusercontent.com/88558377/190157234-520d8925-d67c-4050-807f-97eab7a701d7.png)


**Qual versão é mais fácil de ler?**

![image](https://user-images.githubusercontent.com/88558377/190157824-a2a2821d-be5f-48fd-a37b-24279c315c7f.png)

---------------------------------------
##### Estruturas condicionais

**O que são?**

* A estrutura condicional permite o desvio de fluxo de controle, quando determinadas expressões lógicas são atendidas!

**If**

* Para criar uma estrutura condicional simples, composta por um único desvio, podemos utilizar a palavra reservada if. O comando irá testar a expressão lógica, e em caso de retorno verdadeiro as ações presentes no bloco de código do if serão executadas.

![image](https://user-images.githubusercontent.com/88558377/190159393-32553be7-e4d2-4243-a0ab-3af615892b45.png)


**If/else**

* Para criar uma estrutura condicional com dois desvios, podemos utilizar as palavras reservadas if e else. Como sabemos se a expressão lógica testada no if for verdadeira, então o bloco de código do if será executado. Caso contrário o bloco de código do else será executado.

![image](https://user-images.githubusercontent.com/88558377/190159901-57593445-b6a7-40be-9b27-f0a3d0ba68e3.png)

**If/elif/else**

* Em alguns cenários queremos mais de dois desvios, para isso podemos utilizar a palavra reservada elif. O elif é composto por uma nova expressão lógica, que será testada e caso retorne verdadeiro o bloco de código do elif será executado. Não existe um número máximo de elifs que podemos utilizar, porém evite criar grandes estruturas condicionais, pois elas aumentam a complexidade do código. 

![image](https://user-images.githubusercontent.com/88558377/190160466-83643951-136e-491a-81ca-5c77853026cc.png)










































