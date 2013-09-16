Aula 8
======

Revisão
-------

Capítulo 4
----------

1. Esmeralda não conhece Ronald.

~ (C(e,r))

Os parênteses e vírgulas são opcionais.

Na prova, se houver ambiguidade na hora de denominar os nomes próprios, com as letras minúsculas, especificar o significado de cada item.

Perceber a diferença de nome próprio e variável.

2. Ana é vizinha de Esmeralda.

V(a,e)

3. Ou Olga é vizinha da Ana ou ela é vizinha da Esmeralda.

V(o,a) V V(o,e)

Colocar um `v` no começo está errado.

4. Esmeralda e Ana são colegas de Ronald.

G(e,r) & G(a,r)

Não dá pra usar `c` novamente. Numa mesma máquina, se fizer isso, dá conflito, pois não dá pra usar o mesmo símbolo para nomes próprios diferentes.

(Gear) tá errado porque fica um predicado de três lugares.

Esse tipo de formulação é meio barroca, pois não utiliza a coordenação que usamos em língua natural.

5. Se a Ana*i* conhece a Olga*j*, ela*j* gosta dela*i*.

Capítulo 5
----------

1. Alguém entrou.

∃x (Nx)

∃x Ex V Nx

2. Todo mundo é doido.

∀x (Ex -> Dx)

3. Alguém respeita todo mundo.

∃x ∀y (Ex & Ey -> Rxy)

4. Todo mundo odeia o Cris.

∀x (Ex -> Oxc)

5. Nem toda mulher se respeita.

∃x (Mx & Rxx)

~∀x (Mx -> Rxx)

6. Alguém adora semântica.

∃x (Ex & A(x,s))

7. Tem alguém roubando a Ana.

∃x (Ex & Bxa)

8. (Algum aluno)*i* adora semântica, e a Ana adora ele*i*.

∃x ((Ax) & (Jx,s) & (Ja,x))

O `Jax` tem que estar dentro dos parênteses, senão o `x` fica livre, e não se refere ao mesmo nome próprio.

Deve-se evitar ambiguidades na máquina semântica.

Capítulo 6
----------

1. Maria já tinha se arrumado quando Pedro chegou.

Me -> Mr -> Mf

Dúvida de todos: entre ME e MR, qual é o evento principal? Quando Pedro chegou = ontem - pensar que essa oração é subordinada, e a oração principal corresponde ao ME.
