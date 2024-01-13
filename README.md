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