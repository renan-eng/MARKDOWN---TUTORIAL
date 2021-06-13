# Bem Vindo ao Aprendendo MARKDOWN :wave:

Sumário pode ser feito assim: ``[toc]`` 'Table of contents'.

[toc]

***

### Sintaxes mais comum 

* Os títulos são criados com # no começo da frase e a quantidade de # irá definir o tamanho do título.
* Listas não numeradas são realizadas com * na frente do item
* Para incluir links no seu arquivo utilize os caracteres ``[] e ( )``. Primeiro vem o texto entre colchetes e depois o link em parênteses por exemplo: [meu GitHub pode ser acessado aqui](https://github.com/renan-eng)
* Para exibir o link direto coloque o link entre ''<>'' por exemplo: <https://github.com/renan-eng>
* Acrescentar imagens parecido com inclusão de links porém acrescentando um ponto de interrogação antes do[] e (), por exemplo: ![cachorro](https://pipz.com/static/images/blog/eddie.png)

### Listas numeradas

1. Listas numeradas basta simplesmente colocar o numero da lista e um ``.`` (ponto) depois.
2. Colocar um texto em negrito é simples, envolva seu texto com dois asteriscos ``*``(no começo e no final), dessa forma **Negrito**
3. Coloca em itálico é parecido porem utilize o caractere underline ``_``, dessa forma _itálico_

### Listas desordenadas

* Para realizar uma citação basta usar o símbolo de maior > no começo da frase

* > Isto é uma citação e para continuar a citação na próxima linha basta apertar enter
  >
  > que automaticamente outra linha de citação será criada. Os códigos de **negrito** e 
  >
  > _itálico_ e <https://links.com> também funcionam aqui.

### Código (Code Highlight)

* Para digitar um código em linha (inline) utiliza um acento grave ` no início e no final do código

  `Tudo escrito aqui dentro terá a formatação de linhas de códigos`

* Para digitar várias linhas de códigos pode-se envolver todas as linhas de códigos com três acentos graves ``` ou três tils ~~~~

  ```Tudo escrito aqui dentro terá a formatação de linhas de códigos ```

* Para especificar o tipo de linguagem a ser utilizada basta usar essa sintaxe: ~~~javascript

* Por exemplo:

~~~javascript
Aqui podem ser escritos códigos em javascript.
~~~

~~~php
Aqui podem ser escritos códigos em php.
~~~

~~~~html
Aqui podem ser escritos códigos em hmtl.
~~~~

### Tabela

Após definir os títulos para sua tabela os separe usando o caractere pipe ``|`` e depois use o hífen ``-`` para delimitar a segunda linha e continue separando as colunas com ``|`` conforme abaixo:

```
Exemplo   | Valor do exemplo
--------- | ------
Exemplo 1 | R$ 10
Exemplo 2 | R$ 8
Exemplo 3 | R$ 7
Exemplo 4 | R$ 8
```

Como aparecerá na página:

| Exemplo   | Valor do exemplo |
| --------- | ---------------- |
| Exemplo 1 | R$ 10            |
| Exemplo 2 | R$ 8             |
| Exemplo 3 | R$ 7             |
| Exemplo 4 | R$ 8             |

### Lista de tarefas

Utilizar essa sintaxe no começo da frase ``- [ ]`` irá começar uma lista de tarefas para completar basta marcar com um x desta forma: ``- [x]``. 

- [ ] Primeiro item da lista de tarefas
- [x] Segundo item da lista de tarefas
- [ ] **Terceiro** item da _lista_ de tarefas (negrito e itálico)

- [x] Item completo na lista de tarefas

### Linha Horizontal

Basta digitar três asteriscos ``***`` em uma linha vazia:

***

