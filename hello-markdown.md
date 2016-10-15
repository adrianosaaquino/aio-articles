# Hello Markdown!

Bom, resolvi voltar a escrever porquê além de exercitar um determinado assunto, compartilhar o conhecimento adquirido através da rede, é o minímo que devo fazer como agradecimento.

Irei centralizar todos meus artigos no Github, pois são assuntos técnicos e geralmente irei fazer `referência` a trechos de código que irei armazenar no mesmo.

E também porquê quero aprender escrever no formato (não sei se é o único) utilizado pelo Github, o Markdown, e esse não poderia deixar de ser meu primeiro tema :).

## Vamos ao assunto...

Markdown foi originalmente desenvolvido por John Gruber e Aaron Swartz para escrever documentos duma forma mais simples, e seguindo um determinado padrão, ficaria fácil convertê-lo para o HTML e outros formatos.

### Alguns exemplos

#### Para escrever um texto em itálico, basta escrever o mesmo entre "underscore".
----

<pre>
_Exemplo de texto em itálico_
</pre>

_Exemplo de texto em itálico_

#### Para texto em negrito, coloque a ou as palavras entre asteriscos, atenção, são dois de cada lado.
----

<pre>
**Exemplo de texto em negrito**
</pre>

**Exemplo de texto em negrito**

E sim, podemos utilizar itálico e negrito na mesma linha:

<pre>
Essa frase possui palavras em _itálico_ e em **negrito**.
</pre>

Essa frase possui palavras em _itálico_ e em **negrito**.

E para ter palavras em itálico e negrito, basta misturar ambos.

<pre>
Nossa, uma **_palavra_** em itálico e negrito ao mesmo tempo.
</pre>

Nossa, uma **_palavra_** em itálico e negrito ao mesmo tempo.

####  Utilizando títulos
----

Para se criar um título, basta utilizar o "hash" (#) algumas vezes.

Essa variação pode ir de 1 até 6, sendo convertido entre H1, H2...H6.

<pre>
# Texto com # no início
## Texto com ## no início
### Texto com ### no início, podemos utilizar **negrito no título**, _itálico_ também
#### Texto com #### no início
##### Texto com ##### no início
###### Texto com ###### no início
</pre>

# Texto com # no início
## Texto com ## no início
### Texto com ### no início, podemos utilizar **negrito no título**, _itálico_ também
#### Texto com #### no início
##### Texto com ##### no início
###### Texto com ###### no início


<pre>
Uma outra forma de criar título H1
===============
</pre>

Uma outra forma de criar título H1
===============

<pre>
Uma outra forma de criar título H3
---------------
</pre>

Uma outra forma de criar título H3
---------------

#### Links
----

Para se trabalhar com links, basta colocar entre colchetes o texto que descreve o link e a URL entre parêntese.

<pre>
Visitando o [Google](http://www.google.com)
</pre>

Visitando o [Google](http://www.google.com)

Para inserir uma imagem, seguimos o mesmo modelo, a diferença é que no início inserimos uma exclamação.

<pre>
![Uma imagem do Github](http://brunalab.org/wp-content/uploads/2014/08/blog-github.png)
</pre>

![Uma imagem do Github](http://brunalab.org/wp-content/uploads/2014/08/blog-github.png)

#### Blockquotes
----

As vezes precisamos dar um destaque maior para um texto que está no meio do documento, utilizamos o acento circunflexo no início da frase.

<pre>
> Uma forma de fazer isso utilizando **Blockquotes**, é um bloco de texto em destaque.
</pre>

> Uma forma de fazer isso utilizando **Blockquotes**, é um bloco de texto em destaque.

Podemos utilizar **Blockquotes** com vários parágrafos.

<pre>
> Esse será o primeiro parágrafo.
> O segundo em destaque.
> E um terceiro para exemplificar.
</pre>

> Esse será o primeiro parágrafo.
> O segundo em destaque.
> E um terceiro para exemplificar.

#### Listas
----

Para criar uma lista não ordenada, basta adicionar o asterisco (*) no início de cada frase.

<pre>
* Primeiro item da lista
* Segundo item da lista
* Um terceiro item
</pre>

* Primeiro item da lista
* Segundo item da lista
* Um terceiro item

E para criar uma lista com itens ordenados, muito simples, coloque o número + espaço no início da frase.

<pre>
1. Primeiro item da lista
2. Segundo item da lista
3. Um terceiro item
</pre>

1. Primeiro item da lista
2. Segundo item da lista
3. Um terceiro item

Essas listas podem ter sub-listas, veja como:

<pre>
* Primeiro item da lista
  * Filho do primeiro item
    * Neto do primeiro item
* Segundo item da lista
* Um terceiro item
</pre>

* Primeiro item da lista
  * Filho do primeiro item
    * Neto do primeiro item
* Segundo item da lista
* Um terceiro item

<pre>
1. Primeiro item da lista
  1. Filho do primeiro item
      1. Neto do primeiro item
2. Segundo item da lista
3. Um terceiro item
</pre>

1. Primeiro item da lista
  1. Filho do primeiro item
      1. Neto do primeiro item
2. Segundo item da lista
3. Um terceiro item

#### Parágrafos
----

Você já deve ter notado que ao criar quebra de linha entre parágragos, essa quebra não reflete no texto gerado.

Esse texto é o primeiro parágrafo.
No final do parágrafo anterior, há uma quebra de linha, e nesse também.
Mas isso não reflete na formatação final, observação -> aqui também tem uma quebra de linha.
:(.)

Funcionando:

Esse texto é o primeiro parágrafo.  
No final do parágrafo anterior, há uma quebra de linha, e nesse também.  
Mas isso não reflete na formatação final, observação -> aqui também tem uma quebra de linha.  
:(.)

A diferença é que no final de cada frase do segundo bloco, há dois espaços, isso, dois espaços.

#### Destacando código
----


As vezes precisamos exiber trechos de código:

Um código no meio da frase `código` precisa estar entre aspas invertidas (\`código\`).

Bloco de código:

<pre>
```javascript
var title = "Example JS code";
alert(title);
```
</pre>

```javascript
var title = "Example JS code";
alert(title);
```

<pre>
```java
public static void main(String[] args) {
  System.out.println("Example JAVA code");
}
```
</pre>

```java
public static void main(String[] args) {
  System.out.println("Example JAVA code");
}
```

<pre>
```sql
select count(*), name from table;
```
</pre>

```sql
select count(*), name from table;
```

<pre>
```
def list = ['Item1', 'Item2', 'Item3']
assert list.find { it ==  'Item1'} == 'Item1'
```
</pre>

```
def list = ['Item1', 'Item2', 'Item3']
assert list.find { it ==  'Item1'} == 'Item1'
```

#### Tabelas
----

Podemos criar tabelas também e alinhar seu conteúdo.

<pre>
----- -> alinhar a esquerda
:---: -> alinhar no centro
----: -> alinhar a direita
 </pre>

<pre>
| Esquerda    | Centro  | Direita  |
| ----------- |--------:| --------:|
| Site 1      | 99      | 1        |
| Site 2      | 56      | 2        |
| Site 3      | 23      | 3        |
</pre>

| Esquerda    | Centro  | Direita  |
| ----------- |:-------:| --------:|
| Site 1      | 99      | 1        |
| Site 2      | 56      | 2        |
| Site 3      | 23      | 3        |

<pre>
Site | Número de visitas | Posição
--- | ---
Site 1 | 99 | 1
</pre>

Site | Número de visitas | Posição
--- | ---
Site 1 | 99 | 1

<pre>
Site | Número de visitas | Posição
---: | ---: | ---:
Site 1 | 99 | 1
</pre>

Site | Número de visitas | Posição
---: | ---: | ---:
Site 1 | 99 | 1

<pre>
Site | Número de visitas | Posição
:---: | :---: | :---:
Site 1 | 99 | 1
</pre>

Site | Número de visitas | Posição
:---: | :---: | :---:
Site 1 | 99 | 1


#### Linhas Horizontais
----

Inserir três ou mais:

Hífens  
Asterisco  
Underscore  

<pre>
*******
</pre>



#### Código Markdown não formatado pelo Markdown (han!!!!)

Algumas vezes queremos descrever um trecho de código em Markdown, esse documento mesmo tem vários trechos. Para fazer isso, basta inserir o texto na tag `<pre></pre>`.

```
<pre>
> Um texto num Blockquotes não formatado
</pre>
```

Bom, por enquanto e isso, com o passar do tempo estarei corrigindo e adicionando conteúdo nesse documento.

Um tutorial legal é esse [http://www.markdowntutorial.com/](http://www.markdowntutorial.com/), na verdade é uma sequência de exercícios que recomento a quem quer praticar.

Outras referências:

[Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#videos)  
[JOHN GRUBER Spec](http://daringfireball.net/projects/markdown/)  
[Writing on GitHub](https://help.github.com/categories/writing-on-github/)  
