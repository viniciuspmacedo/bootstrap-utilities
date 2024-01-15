# Bootstrap 5 - Utilidades
Exemplos de uso da biblioteca Bootstrap 5 - Curso Programdorbr

## Adicionando Bootstrap no projeto
Existem algumas maneira de adicionar a Bootstrap ao projeto:
 - a primeira delas através do download do CSS e do JS já compilados, esse método trás como desvantagem o uso de espaço no servidor e o fato do navegador do usuário ter que fazer download do arquivo quando na primeira utilização;
 - a segunda forma é através do código fonte, porém utilizar o código fonte faz mais sentido quando iremos utilizá-lo como base para um outro projeto;
 - a terceira, que será utilizada aqui, é através de uma CDN. Por se tratar de um servidor amplamente utilizado as changes do usuário já ter o arquivo cacheado no seu navegador são grandes;
 - outra maneira é via gerenciadores de pacotes (npm);

## Cores padrões:

A Bootstrap oferece cores padrões para utilização.

## Customização das cores:

É possível fazer a customização das cores do Bootstrap através de um novo arquivo CSS 'lincado' depois do arquivo do Bootstrap alterando a classe ou variável.

### Utilizando o Bootstrap com CSS próprio:

Neste caso as classe do Bootstap irão prevalecer sobre nossas classes uma vez que o Bootstrap usa a 'property' ***!important***;
Para alterar esta prevalecência devemos usar o 'property' ***!important*** na nossa classe.

## Margin e padding:
O Bootstrap oferece 5 níveis de margin e padding, os dois trabalham com a mesma lógica.
Para adicionar uma margem a todos os lados de um elemento utilizamos a classe "m-<'numero'>".
```
<p class="m-1">Margem 1 em todos os lados</p>
```
Para adicionar margem em apenas um lado utilizamos as letras *s, t, e, b*, que se referem a start, top, end e bottom.
Exemplo:
```
<h1 class="mt-5">Margem superior de 5</h1>
``` 
Também é possível aplicar apenas ao eixo x ou y adicionando estas letras à classe.
```
<h2 class="mx-1 my-3">Margem 1 nos lados, margem 3 em cima e embaixo</h2>
```

Para adicionar o padding substituimos o "m" pelo "p".

## Container

A classe container oferece uma maneira fácil de centralizar um conteudo ao seu elemento pai.

## Breakpoint

O Bootstrap é feito pensando no desenvolvimento "mobile-first" e oferece 6 breakpoints padrões:
|propriedade|tamanho|
|-----------|-------|
|xs         |0px    |
|sm         |576px  |
|md         |768px  |
|lg         |992px  |
|xlg        |1200px |
|xxl        |1400px |
|           |       |

Vale lembrar que para utilizar breakpoint devemos usá-lo no nome da classe entre a propriedade e o valor.
{propriedade}-{breakpoint}-{valor}

## Tamanho

Para tamanhos podemos aplicar as propriedades w (width) e h (heigh) seguidas dos valores 0 - 25 - 50 - 75 ou 100 (valores referentes a porcentagem)

## Display

Podemos alterar o display do elemento com a classe "d-inline", "d-inlineblock" ou "d-none"

## Flexbox

Aplica-se o display flex no elemento utilizando a classe "d-flex". A lógica de aplicação é a mesma que no CSS, devemos apenas ficar atentos ao nome da classe.

[link para documentação](https://getbootstrap.com/docs/5.3/utilities/flex/)