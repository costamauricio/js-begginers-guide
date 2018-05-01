# Chapter 1

Preparação do ambiente e primeiro projeto.

## O que eu preciso para começar?

Antes de começar você deve baixar o NodeJs e configurá-lo em sua máquina.

Você pode baixá-lo neste link: https://nodejs.org/en/download/
Recomendo baixar a versão LTS (long time support)

Para escrever o código você precisa de um editor de texto, recomendo o VSCode que tem um bom suporte para javascript.

Você pode baixá-lo aqui:
https://code.visualstudio.com/Download

## Pra que serve esse tal de NodeJs?

Javascript é uma linguagem interpretada, ou seja, após escrito o código é necessário uma engine que consiga interpretar e executar o código. Inicialmente o código javascript era executado somente através dos Browsers (Chrome, Firefox) permitindo que o mesmo fosse executado somente no lado do cliente (o cara que estava acessando determinada página da internet), hoje temo o NodeJs que também nos permite rodar o javascript do lado do servidor, ou seja localmente na máquina como qualquer outra linguagem de programação.

## Como eu sei se instalei o NodeJs corretamente?

Após instalado você pode abrir o terminal (Prompt de comando) e rodar o seguinte comando:

```bash
node -v
```

Como resultado você irá ver a versão que está instalada do NodeJs.

## Como irei submeter o código?

Apartir de agora, todo código que você desenvolver dentro de cada chapter deve ser colocado em arquivos dentro da pasta "code" dentro do respectivo chapter.

Após codificado e testado, o código deve ser comitado para o seu repositório no github e você deve fazer um pull request com o resultado para este repo.

## Meu primeiro programa

#### O que terei que aprender?

* O que é uma variável
* O que é uma função, e o que são parametros da função e retorno da função

#### Links para estudo

* https://canaltech.com.br/software/Fundamentos-do-JavaScript-o-que-sao-e-como-funcionam-as-funcoes/

* https://canaltech.com.br/software/Fundamentos-do-JavaScript-o-que-e-e-como-funcionam-suas-variaveis/

* https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Guide/Values,_variables,_and_literals#Declarations

* https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Guide/Fun%C3%A7%C3%B5es

Os dois primeiros links são bem simples e explicativos, os outros dois já se aprofundam mais nos conceitos. Não se preocupe em entender tudo agora, tente apenas assimilar os conceitos que são necessários para este chapter ;)

#### O desafio

1. Criar um arquivo chamado funcao.js

2. Criar uma função chamada "concatena" que recebe um parametro chamado "texto", coloca este parametro em uma variável chamada "novo_texto", concatena ' world' ao final da variavel "novo_texto" e retorna a variavel "novo_texto"

3. Criar uma variavel chamada "primeiro" e atribuir o valor de 'hello' nesta variável

4. Exibir em tela o resultado da função "concatena" passando a variável "primeiro" como parametro

    -> Para exibir em tela um valor você pode usar a função console.log(...)

#### Como vou rodar meu códigio

Como você criou o arquivo funcao.js e escreveu seu código dentro dele, para rodar o código voce pode executar o seguinte comando:

```bash
node funcao.js
```

Como resultado você deve ver o valor "hello world" em tela. \o/