# tutorialMarkdown
Tutorial de como escrever em Markdown para o meu Blog [Tornando-se um Desenvolvedor](http://melissalobo.blogspot.com.br)

## Títulos

Para marcar um título, você vai usar \# a quantidade de vezes que irá representar o nível do título. Exemplo:

# Título nível 1
## Título nível 2
### Título nível 3
#### Título nível 4
##### Título nível 5
###### Título nível 6

## Parágrafos e quebras de linha

Para gerar parágrafos, basta você escrever o texto em uma linha:

Título de nível 1
==================
  
Título de nível 2
------------------

## Parágrafos e quebras de linha
Para gerar parágrafos, basta você escrever o texto em uma linha:

Este é um parágrafo.
  
Este é outro parágrafo.

Mas a documentação do Markdown diz que, para quebras de linha, você precisa deixar dois espaços no final da linha:

Primeira linha do parágrafo.   [espaço][espaço]
Segunda linha do parágrafo.  
Coloquei o [espaço] no final da primeira linha somente para facilitar a visualização. Você deve substituir por dois espaços em branco.

## Links 
Para gerar links, você usa \[\]\(\). Dentro dos colchetes você coloca o texto do link, e dentro dos parênteses, você coloca a URL:

[Blog da Mel](http://melissalobo.blogspot.com.br)


## Links automáticos

Se o texto do seu link é o próprio link, você pode envolvê-lo entre \< link \>, que o link será gerado automaticamente:

<https://www.google.com.br>


## Listas

Para listas não ordenadas, você pode usar \*, \+ ou \-. Veja:

* Item 1
* Item 2
* Item 3
  
+ Item 1
+ Item 2
+ Item 3
  
- Item 1
- Item 2
- Item 3

## E para listas ordenadas, você usa o número, seguido de ponto:

1. Item 1
2. Item 2
3. Item 3

## Imagens

Geração de imagens é bem parecido com a geração de links: você só precisa adicionar uma \! no início. E o texto que você coloca entre os colchetes, é usado como alt na imagem:

![Eu](https://fbcdn-sphotos-e-a.akamaihd.net/hphotos-ak-xlt1/v/t1.0-9/13124556_984154084999068_6786632002907995125_n.jpg?oh=61d6c4b591caf5ed56d3a71d57d19fc3&oe=5807A2F9&__gda__=1476901864_0192b37cb7089c22bd73bd5c303dcdcc)

## Backslash scapes

Para escapar caracteres que são parseados pelo Markdown, você pode usar a barra invertida \\, seguida do caractere, para imprimi-lo literalmente. O escape funciona para os caracteres listados abaixo:

\\   backslash (barra invertida) <br>
\`   backtick (crase) <br> 
\*   asterisk (asterisco) <br>
\_   underscore <br>
\{}  curly braces (chaves) <br>
\[]  square brackets (colchetes) <br>
\()  parentheses (parênteses) <br>
\#   hash mark (sustenido / hash / jogo da velha) <br>
\+   plus sign (sinal de "mais" ou somar) <br>
\-   minus sign (hyphen) (sinal de menos ou hífen) <br>
\.   dot (ponto) <br>
\!   exclamation mark (ponto de exclamação) <br>

Para saber mais sobre Markdown, recomendo a leitura da documentação oficial:
http://daringfireball.net/projects/markdown/
E alguns links de como o Github usa Markdown, que foi onde eu descobri tudo isso que postei:
https://help.github.com/articles/markdown-basics | https://help.github.com/articles/github-flavored-markdown/
