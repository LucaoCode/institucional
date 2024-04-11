
author: endersonmenezes
summary: Introdução ao Python
id: python-101
categories: python, 101-category
environments: Web
status: Published
feedback link: https://github.com/orgs/codaqui/discussions/new/choose
analytics_ga4_account: G-HT7G6WDWHT
# Python 101 - Aprendendo Python

## Apresentação
Python é uma linguagem de programação Open-Source (código aberto) de propósito geral usado bastante em data science, machine learning, desenvolvimento de web, desenvolvimento de aplicativos, automação de scripts, fintechs e mais.
Essa linguagem de programação foi lançada por Guido van Rossum em 1991.

`Materiais de Referência`:

- [Introdução a Programação Python - IFSP](http://antigo.scl.ifsp.edu.br/portal/arquivos/2016.05.04_Apostila_Python_-_PET_ADS_S%C3%A3o_Carlos.pdf)

- [WikiPython Brasil - Apresentação](https://wiki.python.org.br/PythonApresentacao)

- [Apresentando a Linguagem de Programação Python](https://www.slideshare.net/MayogaX/apresentando-a-linguagem-de-programao-python)

## Introdução à linguagem Python

Nos links disponíveis abaixo será feita uma introdução da linguagem de programação Python.

<video id="3J1xBL7zJXg"></video>

`Materiais de Referência`:

- [Introdução - Python BR](https://python.org.br/introducao/)

## Variáveis e Tipos de Dados em Python

Uma variável é um espaço na memória do computador destinado a um dado que é alterado durante a execução do algoritmo. Para funcionar corretamente, as variáveis precisam ser definidas por nomes e tipos. Nesta aula iremos estudar os tipos de variáveis e suas diferenças.

`Materiais de Referência`:

- [Tipos de Dados - Algorítimos em Python](https://algoritmosempython.com.br/cursos/programacao-python/tipos-basicos/)

- [Variáveis - USP](https://panda.ime.usp.br/cc110/static/cc110/03-variaveis.html)

`Material Complementar:`

- [Tipos de Variáveis - PythonAcademy](https://pythonacademy.com.br/blog/tipos-de-variaveis-no-python)

## Estruturas Lógicas e Condicionais em Python
As estruturas condicionais permitem que um programa execute diferentes comandos de acordo com as condições estabelecidas. Aqui, estudaremos suas aplicações e formatos.

A estrutura condicional é uma seção que ajuda a definir condições para a execução de algum algoritmo, ao invés de executar tudo de uma vez, sem nenhuma interrupção, o programa realiza verificações e valida as condições impostas pelo programador.

É como uma bifurcação, um momento importante para realizar a tomada de decisão. Nesse caso, essa decisão é resultado de alguma análise, de comparação.

Funciona da seguinte maneira: Se essa condição X for satisfeita, execute esse bloco;senão execute outro bloco de comando.

Em um fluxograma conseguimos visualizar melhor como ficaria esse caso.

**Foto do fluxograma**

**Estruturas condicionais no código**

Na linguagem de programação Python a estrutura condicional é representada por “IF” e “ELSE”, Esses dois termos vem originalmente da língua inglesa, que em português o “IF” significa “SE” ,e “ELSE” significa “SENÃO”.
Desta forma talvez possa facilitar a sua compreensão ao ler o código escrito de Python.

```python3
Em Python podemos escrever da seguinte maneira a estrutura condicional “IF” e “ELSE”

IF (Condição onde o resultado tem que ser um valor booleano):
	Resultado da condição caso o resultado for verdadeiro
ELSE:
Resultado da condição caso o resultado for falso
```

Em Python podemos ramificar a condição para mais de dois resultados utilizando o “ELIF”. O “ELIF” é uma estrutura intermediária dentro da seção if-else no python, quando você já tem um “IF” e um “ELSE”, ao invés de criar mas if-else você apenas adiciona o “ELIF” entre eles para especificar alguma outra regra.

Como exemplo ficaria desta forma:

```python3
IF (Condição onde o resultado tem que ser um valor booleano):
	Resultado da condição caso o resultado for verdadeiro
ELIF (Segunda condição onde o resultado retorna verdadeiro):
	Resultado da segunda condição quando verdadeira
ELSE:
Resultado da condição caso o resultado for falso
```
Expressões booleanas

Uma expressão booleana é uma expressão que pode ser verdadeira ou falsa. Como os exemplos seguintes

```python3
type(true)
retorna bool
type(false)
retorna bool
```

É importante ressaltar que True e False são do tipo booleano e não strings
O operador == é um dos operadores relacionais

```python3
5 == 5
# retorna true
5 == 6
retorna false
```

Neste exemplo ele compara se um valor é igual ao outro e retorna um valor booleano
Embora essas operações sejam familiares para você, os símbolos do python são diferentes dos símbolos matemáticos. Um erro muito comum é colocar apenas um sinal de (=) ao invés de um sinal duplo (==). Lembre-se que o (=) é um operador de atribuição e o (==) é um operador relacional.

Mais alguns exemplos de expressões booleanas

```python3
if nome == # igual
if nome != # diferente
if nome >= # maior ou igual
if nome <= # menor ou igual
if a in nome # esta dentro
if a in lista
if is true # é verdadeiro
```

**Operadores Lógicos**

Há três operadores lógicos: and,or e not. A semântica (significado) destes operadores é semelhante ao seu significado em inglês.

**Exemplo**:
```python3
x > 0 and x < 10 # Só é verdadeiro se x é menor que 10 e maior que 0
x == 0 or x == 10 # só é verdadeiro se x é igual a 10 ou igual a 0
```
O operador not, nega uma expressão booleana, então not(x>y) é verdade se x > y for falso,isto é, se x for menor que ou igual a y

`Materiais de Referência`:

- [Estruturas e Condicionais - #Treinamentos](https://www.hashtagtreinamentos.com/estruturas-condicionais-no-python)

- [Operadores Lógicos - Caravela](https://pense-python.caravela.club/05-condicionais-e-recursividade/00-condicionais-e-recursividade.html)

## Estruturas de Repetição em Python

Estruturas de repetição são estruturas que permitem a execução de instruções repetidas vezes, até que uma condição seja atingida.

Estruturas de repetição é uma estrutura lógica que permite executar mais de uma vez o mesmo comando ou conjunto de comandos, podendo ser utilizada para repetir um mesmo processamento até que a condição seja satisfeita ou até mesmo para repetir ações semelhantes que são executadas para todos os elementos de uma lista de dados. As estruturas de repetição vão fazer alguma tarefa repetitiva de forma automática.

`Materiais de Referência`:

- [Estruturas de Repetição - DevMedia](https://www.devmedia.com.br/estruturas-de-repeticao-em-python/41551)

- [Estruturas de Repetição - #Treinamentos](https://www.hashtagtreinamentos.com/estruturas-de-repeticao-python)

## Coleções Python
As coleções permitem armazenar múltiplos itens dentro de uma única unidade, que funciona como um container. Neste tópico iremos ver quais são e como usa-las.

`Materiais de Referência`:

- [Coleções no Python](https://www.devmedia.com.br/colecoes-no-python-listas-tuplas-e-dicionarios/40678)

- [Python sequências e coleções](https://www.phylos.net/2021-03-08/python-sequencias-e-colecoes/)

`Vídeo Complementar:`

- [Coleções em python - Aprenda dicionário resumidamente)](https://youtu.be/2Q4GkMQ-vzQ)

## Funções em Python
Após passarmos pela Seção 7, vamos comentar sobre as Funções em Python. São blocos de códigos que só são executados quando chamados, podemos passar dados (os famosos parâmetros), e depois retornar alguma resposta.

`Materiais de Referência`:

- [Funções](https://algoritmosempython.com.br/cursos/programacao-python/funcoes/)

- [Funções 2](https://panda.ime.usp.br/pensepy/static/pensepy/05-Funcoes/funcoes.html)

- [Funções 3](https://www.dcc.ufrj.br/~fabiom/mab225/07func.pdf)

`Vídeo Complementar:`

- [Um Programador Pleno já deveria saber usar esse Design Pattern (tutorial linha a linha)](https://youtu.be/arAz2Ff8s88?t=111)

## Comprehensions em Python

As Comprehensions em Python serve para escrever uma nova lista baseada em outra lista existente de uma maneira mais curta, deixando mais fácil de entender e mais simples de ler o código.

`Materiais de Referência`:

- [Comprehensions no Python](https://pythonacademy.com.br/blog/list-comprehensions-no-python)

- [Comprehension](https://pythonhelp.wordpress.com/2011/03/01/list-comprehension/)

## Expressões Lambdas e Funções Integradas

Uma expressão lambda permite escrever funções anônimas/sem nome usando apenas uma linha de código. As funções integradas são funções que permitem obter alguma informação a respeito de uma variável de tipo padrão ou transformar o tipo de uma variável. Neste tópico, podemos aprender mais profundamente sobre ambas.

`Materiais de Referência`:

- [Função Lambda](https://www.codingame.com/playgrounds/52499/programacao-python-intermediario---prof--marco-vaz/funcao-lambda)

- [Funções Lambda em Python](https://www.hashtagtreinamentos.com/funcoes-lambda-python)

- [Lambda](https://pythonhelp.wordpress.com/tag/lambda/)

- [Guru99 - Lambda Functions Examples](https://www.guru99.com/python-lambda-function.html)

## Debugando e Tratando erros
Debugar é encontrar e corrigir erros de um programa. Nesse tópico iremos ver como tratar erros e exceções.

`Materiais de Referência`:

- [Erros de sintaxe (Syntax errors)](https://panda.ime.usp.br/panda/static/pensepy/Appendices/app_a.html)

- [Entendendo melhor as mensagens de erro](https://pythonhelp.wordpress.com/2012/12/31/deu-erro-e-agora-o-que-eu-faco/)

## Trabalhando com Módulos Python

Módulos em Python são arquivos contendo definições e comandos a serem utilizados em outros programas na mesma linguagem, utilizando a `keyword import`.

Conforme a introdução do segundo _link_ de estudo, a importação de módulos só é possível enquanto dentro do mesmo diretório, ou se estiver em uma lista de diretórios dadas pela variável `sys.path`, começada no diretório atual e procurada na variável `PYTHONPATH` do **Shell**, por fim no diretório padrão que depende da instalação.

Leia mais a respeito de **módulos** nos _links_ de estudo abaixo.

`Materiais de Referência`:

- [Como criar um módulo](https://www.pythonprogressivo.net/2018/07/import-Como-Criar-Importar-Usar-Modulo-Python-Curso.html)

- [Módulos-Executando módulos como scripts](https://docs.python.org/pt-br/3/tutorial/modules.html)

## Leitura e Escrita em Arquivos

Os computadores utilizam os arquivos como estruturas de dados, por exemplo, vídeos, imagens e planilhas. Nesta aula, vamos aprender como os programas em Python criam, recuperam, atualizam e processam arquivos de dados, ou seja, manipulam arquivos.

`Materiais de Referência`:

- [Abrindo, fechando e lendo arquivos (Com exercícios)](https://panda.ime.usp.br/pensepy/static/pensepy/10-Arquivos/files.html)

- [Como escrever e salvar arquivos JSON em Python](https://academiahopper.com.br/trabalhando-com-arquivos-em-python/)
- [Manipulando arquivos - FreeCodeCamp](https://www.freecodecamp.org/portuguese/news/como-escrever-em-um-arquivo-em-python-open-read-append-e-outras-funcoes-de-manipulacao-explicadas/)

## Iteradores e Geradores Python

Iterator em python é um objeto que é usado para iterar sobre objetos iteráveis, como listas, tuplas, dicts e conjuntos.
Os geradores em Python são uma maneira simples de criar um objeto iterável sem a necessidade de construí-lo dentro de uma classe. Um objeto iterável consiste em um conjunto finito de dados cujo conteúdo é tratado um elemento por vez, iniciando do primeiro e seguindo até o último, quando a iteração é terminada.

`Materiais de Referência`:

- [Iterators e Generators em Python - Python Academy]( https://pythonacademy.com.br/blog/iterators-e-generators-em-python)

- [Iteradores, iteráveis e geradores - ICHI.PRO]( https://ichi.pro/pt/iteradores-iteraveis-e-geradores-132206850510725)

- [Diferença entre iteradores e geradores do Python - QA Stack]( https://qastack.com.br/programming/2776829/difference-between-pythons-generators-and-iterators)


## Decoradores em Python

Saindo dos iteradores e geradores, seguiremos com decoradores em python. Para simplificarmos sua ideia, podemos dizer que eles são funções que modificam a funcionalidade de uma outra função.

`Materiais de Referência`:

- [Decoradores por Python Iluminado](https://pythoniluminado.netlify.app/decoradores)

- [Decoradores por Python WIKI](https://wiki.python.org.br/Decoradores_Python_(Python_Decorators))

- [Como funcionam os decoradores em Python?](https://pt.stackoverflow.com/questions/23628/como-funcionam-decoradores-em-python)

## Orientação a Objetos com Python

Programação orientada a objetos (POO) é um paradigma de programação baseado no conceito de "objetos", que podem conter dados na forma de campos, também conhecidos como atributos, e códigos, na forma de procedimentos, também conhecidos como métodos.

`Materiais de Referência`:

- [Classes](https://panda.ime.usp.br/pensepy/static/pensepy/13-Classes/classesintro.html)

- [Python Orientado a Objetos com Framework CherryPy](https://www.devmedia.com.br/python-orientado-a-objetos-com-o-framework-cherrypy/33489)

- [Programação Orientada a Objetos com Python](https://wiki.python.org.br/ProgramacaoOrientadaObjetoPython)

## Herança e Polimorfismo

Herança é um mecanismo importante quando um grupo de classes apresenta a mesma interface, mas a implementação interna dos métodos é diferente. Polimorfismo é a capacidade que uma subclasse tem de ter métodos com o mesmo nome de sua superclasse, e o programa saber qual método deve ser invocado, especificamente.

`Materiais de Referência`:

- [Polimorfismo - O que é e como usar?](https://www.pythonprogressivo.net/2018/11/Polimorfismo-O-que-Como-Usar-Como-fazer.html)

- [Entendendo o Super() do Python](https://medium.com/code-rocket-blog/entendendo-o-super-do-python-da17ee8d26ca)

- [Conceitos de Polimorfismo em POO](https://www.devmedia.com.br/conceitos-e-exemplos-polimorfismo-programacao-orientada-a-objetos/18701)

## Manipulando Arquivos CSV e JSON

O arquivo CSV (valores separados por vírgulas) é um arquivo de texto com formato específico para possibilitar o salvamento dos dados em um formato estruturado de tabela. O formato JSON (JavaScript Object Notation) é utilizado para estruturar dados em formato de texto e permitir a troca de dados entre aplicações de forma simples, leve e rápida.

`Materiais de Referência`:

- [importando dados com Python](https://imasters.com.br/back-end/data-science-importando-dados-com-python)

## Trabalhando com Data e Hora em Python

Registrar um momento qualquer no tempo é um requisito comum em todo sistema usual. Esse registro pode ser em data e hora. É comum fazer operações com esses dados, portanto, sua precisão é muito importante.

`Materiais de Referência`:

- [Como trabalhar com data hora Python](https://vaiprogramar.com/como-trabalhar-com-data-hora-python-datetime/)

- [Tipos básicos de data e hora](https://docs.python.org/pt-br/3/library/datetime.html)

- [Trabalhando com datas e horas em Python](https://pythonhelp.wordpress.com/2012/07/10/trabalhando-com-datas-e-horas-em-python-datetime/)

## Testes com Python

Os testes servem para antecipar e corrigir falhas e bugs que apareceriam para o usuário final. Neste tópico iremos apresentar como fazer testes em um programa.

`Materiais de Referência`:

- [Testes em Python parte I](https://dev.to/womakerscode/testes-em-python-parte-1-introducao-43ei)

## Encerramento

Neste tópico iremos abordar comandos que podem ser usados para fechar um programa escrito na linguagem Python.

`Materiais de Referência`:

- [Finalizando um script Python - QA Stack]( https://qastack.com.br/programming/73663/how-to-terminate-a-python-script)


## Gerenciamento de Memória em Python

Quando criamos uma variável em Python, essa variável é armazenada na memória do computador. A alocação de memória pode ser definida como a alocação de um bloco de espaço na memória do computador para um programa. Nesta aula iremos entender como funciona o gerenciamento de memória do computador.

`Materiais de Referência`:

- [Gerenciamento de memória Python – Weekly-Geekly ES]( https://weekly-geekly-es.imtqy.com/articles/pt441568/index.html)


## Checagem de Tipos em Python

Neste tópico você vai aprender a como checar o tipo de uma variável em Python, ou seja, saber qual o tipo de dado uma variável contém.

`Materiais de Referência`:

- [Checando os tipos de variáveis em Python 3 - Hora de Codar]( https://www.horadecodar.com.br/2021/03/30/como-checar-o-tipo-de-uma-variavel-em-python-3/)

- [Checagem de tipos no Python - gutierri]( https://medium.com/gutierri/checagem-de-tipos-no-python-1533fe1e786f)


## Interagindo com o sistema operacional

Há momentos no desenvolvimento de uma aplicação que precisamos interagir com o sistema operacional para acessar diretórios, criar arquivos, executar comandos entre outras ações, e para isso contamos com algumas bibliotecas nativas do Python, como [os](https://docs.python.org/pt-br/3/library/os.html) e [subprocess](https://docs.python.org/pt-br/3/library/subprocess.html), que nos auxiliam nesses processos.

`Materiais de Referência`:

- [Executando comandos Shell - TechExpert Tips](https://techexpert.tips/pt-br/python-pt-br/python-executando-comandos-shell/)
- [Interagindo com o sistema operacional - TecnoGuia](https://tecnoguia.istocks.club/o-que-e-o-modulo-os-do-python-e-como-usa-lo/2021-03-15/)


## Consumindo dados de fontes externas

Neste tópico será abordado formas de trabalhar com dados provenientes de fontes externas, como um site ou outra aplicação.

O Python disponibiliza nativamente a biblioteca [urllib](https://docs.python.org/pt-br/3/library/urllib.html) para efetuar requisições a sites, APIs, entre outras, mas existe uma outra biblioteca, de terceiros, chamada [requests](https://requests.readthedocs.io/) que é bem mais simples que pode ser utilizada para fazer realizar esse tipo de tarefa.

`Materiais de Referência`:

- [Como usar Urllib - Ciksiti](https://ciksiti.com/pt/chapters/5031-how-to-use-urllib-in-python--linux-hint)
- [Consumindo a API do Github - Alura](https://www.alura.com.br/artigos/consumindo-a-api-do-github-em-python)

## Ambiente de Desenvolvimento Local

Aqui é fornecido guias para a instalação de compiladores de Python.

`Materiais de Referência`:

- [Configurando um ambiente de desenvolvimento Django](https://developer.mozilla.org/pt-BR/docs/Learn/Server-side/Django/development_environment)

- [Instalação do Django](https://tutorial.djangogirls.org/pt/django_installation/)

- [Guia definitivo para organizar meu ambiente Python](https://medium.com/welcome-to-the-django/guia-definitivo-para-organizar-meu-ambiente-python-a16e2479b753)

- [Flask no Replit](https://replit.com/talk/learn/Flask-Tutorial-Part-1-the-basics/26272)

- [WSL no Windows](https://docs.microsoft.com/pt-br/windows/wsl/install)

## Novidades

### Novidades do Python 3.8

Vamos conhecer a versão 3.8 no Python. A nova versão apresenta novas funcionalidades, entre elas estão as expressões de atribuição e os parâmetros apenas posicionais.

`Materiais de Referência`:

- [Python 3.8 lançado com expressões de atribuição e mais](https://www.edivaldobrito.com.br/python-3-8-lancado-com-expressoes-de-atribuicao-e-mais/)

- [O que há de novo no Python 3.8](https://docs.python.org/pt-br/3/whatsnew/3.8.html)

### Novidades do Python 3.9

Vamos conhecer a versão 3.9 no Python. A nova versão apresenta novas funcionalidades, entre elas estão os operadores de mesclagem & atualização de dicionário e novos métodos de strings para remover prefixos e sufixos.

`Materiais de Referência`:

- [O que há de novo no Python 3.9](https://docs.python.org/pt-br/3/whatsnew/index.html)

- [Atualizações do Python 3.9 explicadas com exemplos práticos de código](https://cibersistemas.pt/tecnologia/atualizacoes-do-python-3-9-explicadas-com-exemplos-praticos-de-codigo/)

- [Python 3.9 lançado com melhorias em multiprocessamento e novo analisador](https://www.edivaldobrito.com.br/python-3-9-lancado-com-melhorias-em-multiprocessamento-e-novo-analisador/)


### Novidades do Python 3.10

Vamos conhecer a versão 3.10 no Python. A nova versão apresenta novas funcionalidades, entre elas estão a correspondência de padrões estruturais e gerenciadores de contexto entre parênteses.

`Materiais de Referência`:

- [O que há de novo no Python 3.10](https://docs.python.org/pt-br/3.10/whatsnew/index.html)

- [What’s New in Python 3.10?](https://towardsdatascience.com/whats-new-in-python-3-10-a757c6c69342)

- [What’s new in Python 3.10](https://www.infoworld.com/article/3617460/whats-new-in-python-310.html)

## Discussões

As discussões para atualizações e sugestões aprovadas foram realizadas aqui:

- [Atualização 1 - PR#6](https://github.com/codaqui/institucional-trilhas-estudos/pull/6)
- [Atualização 2 - PR#7](https://github.com/codaqui/institucional-trilhas-estudos/pull/7)
- [Atualização 3 - PR#78](https://github.com/codaqui/institucional/pull/78)

Se você deseja alterar algo, inicie uma nova discussão [clicando aqui.](https://github.com/orgs/codaqui/discussions/new/choose)

## Bibliografia

Inicialmente a trilha de conteúdos usada foi do curso do Geek University, e posteriormente a [@melissarr](https://github.com/melissarr) fez um trabalho de agrupamento e pesquisa dessa trilha em diversos portais. A partir desse trabalho de agrupamento e pesquisa da [@melissarr](https://github.com/melissarr):

- [@pedrocvaranda](https://github.com/pedrocvaranda) organizou os tópicos "Introdução à linguagem Python", "Variáveis e Tipos de Dados em Python", "Estruturas Lógicas e Condicionais em Python", "Estruturas de Repetição em Python" e uma parte da "Bibliografia".
- [@melissarr](https://github.com/melissarr) organizou os tópicos: "Debugando e Tratando erros", "Trabalhando com Módulos Python" e "Leitura e Escrita em Arquivos".
- [@kamisinha](https://github.com/kamisinha) organizou os tópicos: "Novidades do Python 3.8", "Novidades do Python 3.9" e "Novidades do Python 3.10".
- [@LuizFernando-TC](https://github.com/LuizFernando-TC) organizou os tópicos: "Iteradores e Geradores Python", "Encerramento", "Gerenciamento de Memória em Python" e "Checagem de Tipos em Python". Ajudou a criar resumos de diversas categorias,
- [@isiezz](https://github.com/isiezz) organizou os tópicos: "Manipulando Arquivos CSV e JSON", "Trabalhando com Data e Hora em Python" e "Testes com Python".
- [@caiodocoduiguin](https://github.com/caiodocoduiguin) organizou os tópicos: "Coleções Python", "Funções em Python", "Comprehensions em Python" e "Expressões Lambdas e Funções Integradas".

## Certificação Codaqui

<img src="./assets/python-101/certificado-python.png">

> aside positive
> Você deseja obter a certificação Codaqui para trilha de desenvolvimento em Python? Inscreva-se [clicando aqui.](https://classroom.github.com/a/NxcWpy-1)

> Recomendamos que estude antes de se inscrever, e caso tenha qualquer dúvida entre em contato por e-mail [contato@codaqui.dev](mailto:contato@codaqui.dev)
