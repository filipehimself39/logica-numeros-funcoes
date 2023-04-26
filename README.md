# lógica, números e funções - sala 206, bloco G

![paprika](https://user-images.githubusercontent.com/128937668/233802088-42a015e3-3023-4586-a88a-b8b196d52c68.gif)

prova 1: 15/05 prova 2: 28/06

## Introdução à lógica

**Termos**

São as expressões ou "palavras" da linguagem matemática. Designam uma coisa, uma qualidade ou uma ideia.

Por exemplo: a+b; diagonal do quadrado; AÔB; xy2; triângulo; reta; π.

---

**Enunciados**

São as sentenças ou "frases" da linguagem matemática. São composições com termos que têm um determinado sentido.

Exemplos:

1. Não existe a divisão por zero.

2. A soma dos ângulos internos de um triângulo são 180.

3. (x+y)(x-y) = x2 - y2

---

**Variáveis**

São elementos representados por letras, que num enunciado ou termo podem ser substituídos por elementos de um conjunto indicado pelo enunciado ou pelo termo.

Exemplos:

1. No termo 2x + 1, x é a variável que pode ser substituída por qualquer número.

2. No enunciado (x-y)(x+y) = x2 - y2, as variáveis x e y podem ser substituídas por números quaisquer, 2 e 3 por exemplo, e obteremos: (2-3)(2+3) = 4 - 9.

3. Em x2 - 2x - 3 = 0 podemos substituir x por 2 e 3, encontrando 4 - 4 - 3 = 0 e 9 - 6 - 3 = 0 respectivamente.

**Nota:** O enunciado 4 - 4 - 3 = 0 tem sentido coerente, mas é falso.

---

**Termos primitivos**

São termos que não se definem numa linguagem. São chamados conceitos primitivos. Por exemplo: ponto, reta, plano, conjunto, elemento e pertinência.

---

**Axiomas**

São enunciados considerados verdadeiros. São relações entre termos primitivos que não se demonstram. Parte-se deles para demonstrar outros enunciados.

**Nota:** axiomas são verdades aceitas sem demonstração.

Exemplos:

1. dois pontos determinam uma reta.

2. dois conjuntos são iguais se, e somente se, têm os mesmos elementos.

3. Existe um conjunto N, chamado conjunto dos números naturais, que possui 0 e o sucessor de cada um dos seus elementos (n' é sucessor de n se n' = n + 1).

---

## **Proposições**

São enunciados aos quais se pode atribuir a qualidade de serem verdadeiros ou falsos. Assim, o valor verdade ou lógico da proposição será V ou F.

Exemplos:

1. 3 + 5 = 8 (V)

2. Paris é capital do Brasil. (F)

3. O camelo é um peixe. (F)

4. Todo múltiplo de 4 é par. (V)

---

**Função proposicional ou sentença aberta**

São enunciados em que constam uma ou mais variáveis.

Não são por si só proposições. Tornam-se proposições quando se atribuem às variáveis valores de certo conjunto.

Exemplos:

1. x é capital do Brasil.
* Se x = Brasilía, então temos uma proposição verdadeira.
* Se x ≠ Brasilía, então temos uma proposição falsa.

2. x + 1 > 5
* Se x > 4, então temos uma proposição verdadeira.
* Se x ≤ 4, então temos uma proposição falsa.

---

**Proposições simples e compostas**

Chamam-se **proposições simples** aquelas que têm um só sujeito e um só predicado.

Exemplos:

p: Maria é nome de mulher. (V)
q: 12 é um número par. (V)
r: os números pares são primos. (F)

Chamam-se **proposições compostas** todas as proposições que se obtêm combinando-se duas ou mais proposições simples.

Exemplos:

Sejam p e q as proposições:

p: Carmen é bela.
q: Filipe é inteligente.

Essas duas proposições simples podem ser combinadas formando várias proposições compostas distintas:

1. Carmen é bela **e** Filipe é inteligente.

2. Carmen é bela **ou** Filipe é inteligente.

3. Se Carmen é bela **então** Filipe é inteligente.

4. Carmen é bela **se, e somente se** Filipe é inteligente.

---

As diversas maneiras de formar uma proposição composta a partir das simples serão analisadas quando estudarmos os **conectivos lógicos**.

---

## Tabelas verdade

São tabelas que reúnem todas as hipóteses possíveis quanto aos valores verdade de uma proposição.

1. Considerando apenas uma proposição *p* temos apenas duas hipóteses: V ou F.

p
---|
V
F

2. Considerando duas proposições *p* e *q* temos 4 hipóteses.

p | q
---|---|
V | V
V | F
F | V
F | F

**nota**: a proposição composta será constituída por apenas um dos 2^2=4 passos possíveis.

3. Considerando três proposições p, q e r, temos 8 hipóteses que são obtidas analogamente:

p | q | r
---|---|---|
V | V | V
V | V | F
V | F | V
V | F | F
F | V | V
F | V | F
F | F | V
F | F | F

**nota**: basta combinar cada hipótese anterior, com V ou F da terceira, dando 2^2*2 = 2^3 = 8 casos possíveis.

**generalizando**: assim, para n proposições, o número total de casos será 2^n.

---

**Proposições equivalentes**

Duas proposições p e q são equivalentes exatamente quando têm a mesma tabela verdade, isto é, têm os mesmos valores lógicos nas mesmas situações.

Usa-se a notação: p <-> q e se lê 'p se, e somente se, q' ou 'p é equivalente a q'.

**exemplo**: define-se um triângulo equilátero como aquele que tem lados iguais.

assim, estabelecemos a equivalência:

ABC é equilátero <-> AB = AC = BC

---

**1.a.** 3>1 **e** 4>2; verdadeira.

**b.** 3>1 **ou** 3=1; verdadeira.

**c.** 2|4 **ou** 2|(4+1); verdadeira.

**d.** 3(5+2) = 3 * 5 + 3 * 2 **e** 3|7; falsa.

**e.** falsa.

**f.** falsa.

**g.** falsa.

**2.** a negação de x ≥ -2? x < -2.

**3.**

---

## Conjuntos

**Noções fundamentais**

**Conceito**

O conceito de conjunto é primitivo, uma noção primária não definida. Intuitivamente, conjunto é uma classe de "elementos bem definidos".

Esses "elementos bem definidos", concretos ou abstratos, são em geral agrupados segundo critérios determinados ou propriedades exclusivas, dando origem aos conjuntos.

Um conjunto está definido se for possível decidir, sem ambiguidade, se um dado elemento pertence ou não a ele.

Não são considerados conjuntos (no nosso contexto) as coleções em que, para decidir se um elemento é ou não membro do conjunto, tem-se que dar interpretações subjetivas.

**exemplos de conjuntos:**

1. Conjunto dos alunos de uma turma.

2. Conjunto das turmas do colégio.

3. Conjunto dos colégios do estado do Rio de Janeiro.

4. Conjunto dos estados do Brasil.

5. Conjunto dos países de um continente.

6. Conjunto dos continentes da Terra.

7. Conjunto dos planetas do Universo.

**contra exemplos**, isto é, não são conjuntos no nosso contexto:

1. Conjunto dos problemas fáceis.

2. Conjunto dos alunos inteligentes.

3. Conjunto das flores bonitas.

4.  Conjunto das cidades próximas.

Observe que, em cada um desses enunciados, seria necessário dizer o que se entende por fácil, inteligente, bonito e próximo, para que se pudesse decidir se um elemento faz ou não parte da coleção em questão.

Representam-se em geral os conjuntos por letras maiúsculas A, B,...,X, Y e seus elementos pelas letras minúsculas correspondentes a, b,..., x, y.

**Pertinência**

É um conceito primitivo, não tem definição.

Para indicar que um elemento x pertence ao conjunto X usaremos a notação: x ∈ X, que se lê: "o elemento x pertence ao conjunto X".

A negação da propriedade de pertinência se representa por y ∉ X, que se lê: "o elemento y não pertence ao conjunto X".

**exemplos:**

1. Seja H o conjunto dos seres humanos. Seja o ser humano Anna e o planeta Marte. Temos Anna ∈ H e Marte ∉ H.

2. Seja C o conjunto dos números inteiros compreendidos entre 10 e 20. Temos então 17 ∈ C e 25 ∉ C.
