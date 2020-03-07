**Axioma da infinitude e os naturais.**

**Axioma da infinitude** : Existe uma função $$S:X \rightarrow X$$ injetora e
não sobrejetora.

O leitor pode contestar e dizer que isso não define, em parte, um conjunto
infinito. De fato, nessa formulação do axioma da infinitude, a captação real do
infinito não é tão intuitiva de se ver, por isso irei tentar mostrar melhor
porque é assim. O fato é que em todo conjunto X finito, para toda função S que
$$S:X \rightarrow X$$ e que essa mesma função é injetora, ela é,
necessariamente, sobrejetora pelo simples fato de que se ela não for
sobrejetora, existe pelo menos um que não tem uma antiimagem S[x]. Ora, mas
sabemos que pela condição de injectividade, se o conjunto X tem cardinalidade
\|X\| = n tal que(os naturais) – já que X é finito – todos os n devem ter
imagens distintas; isso implica que não pode existir nenhum n que não tenha
antiimagem, pois se existir, existiram n-1 elementos possíveis na imagem, algo
que é contrário á hipótese de que existam n elementos distintos em X;
contradição, logo X é **infinito**. Outra característica dessa função é a
seguinte: Se essa função existe mesmo em X(e existe porque postulamos), todos os
elementos de X possuem imagens distintas deles mesmo, caso contrário tal função
não seria não sobrejetora, já que seria uma função identidade, logo bijectora e
uma nova contradição com o postulado. Ora, já sabemos que tal função S associa
para cada um S(x) diferente de x e diferente de qualquer S(y) para yx, o que só
é verdade se X for um conjunto infinito e para todo se , logo S(x)$$\neq$$ S(y).
Vamos tentar tirar proveitos de tais resultados de uma forma mais visível

**Teoremas 1.0 (** os chamados axiomas de Peano): Existe um conjunto N, com uma
função e outro conjunto 0 de modo que se satisfaça as seguintes propriedades:

1.

2. Se

3. Não existe nenhum n tal que S(n) = 0

4.Se n,m N, S(n) = S(m), logo m = n.

5. Se um conjunto AN tem a propriedade de que 0A e sempre que nA

S(n) A, logo A = N.

**Demonstrações:** Pois bem, a maioria dessas propriedades já foram provadas nas
nossas elucidações do axioma da infinitude. Por exemplo, a propriedade 3 se
segue simplesmente do fato de que a função é injectiva e ela gera sempre um
conjunto diferente não nulo(0). 2 se segue da própria natureza infinita do nosso
conjunto e pal própria definição de função : S(n) sempre deve pertencer ao
conjunto X se não teríamos uma função mal formado, com algum elemento do domínio
sem uma imagem, e assim nós vamos demonstrando os outros. *Porém, perceba que os
nossos teoremas fazem uma referência á um conjunto N e não á um X*; isso ocorre
porque o que queremos é o menor conjunto que tem as propriedades indutivas de X.
Então vamos lá: vamos fazer uso do nosso axioma da infinitude. Seja uma função
injetora e sobrejetora de acordo com o axioma; vamos eleger uma elemento 0 de X
que não tem uma antiimagem pela função S. Diremos que um conjunto AX é indutivo
se 0 A e quando n A podemos demonstrar que S(n) A. Iremos chamar de J a classe
de todos os conjuntos indutivos:

$$J = \{ A|A \subset X \land A$$ é indutivo}

Observe que , já que, no mínimo, X J. Seja um N tal que . Assim N X, pelo axioma
das partes, N é um conjunto(veja que estamos pressupondo a teoria NGB de
conjuntos, para mais detalhes ver as referências e, talvez, em outro momento,
posso fazer algum post aqui comentando alguns axiomas e algumas teorias dos
conjuntos). Perceba que 0 N, já que para todo conjunto J, pela definição de
conjunto indutivo e por N pertencer a J, 0 N. Claramente o mesmo para 2, já que
N é indutivo. A propriedade 3 se segue porque nos escolhemos o 0 como o elemento
de X que não possui uma antiimagem e, como 0 pertence a N, logo nos demonstramos
o que queremos demonstrar. A propriedade 4 se segue pelo que já falamos da
natureza indutiva e, principalmente, pela injectividade. A propriedade 5 se
segue para N porque N é o menor conjunto indutivo de X e A é indutivo, logo N A,
mas se A N por hipótese, logo A = N. Podemos chamar tais restrições da função S
para N de : . É necessário se atentar para entender bem o quinto teorema, já que
é o famoso princípio de indução. Perceba que quando se fala nesse princípio,
sempre se fala sobre valer para 0 e supondo que vale para n então vale para
S(n), logo vale para todos x que pertencem á N. Ora, do jeito que nós formulamos
isso ainda não parece certo. O certo é que o que nós falamos é que,
simplesmente, estamos dando condições suficientes para que, para qualquer dado
conjunto, tal conjunto seja igual a N. Porém, ficará claro mais tarde que, nosso
princípio, do jeito que nós formulamos, é base das provas por indução; o que se
quer nessas provas não é provar que um conjunto A qualquer é igual a N. O que se
deseja é provar que uma certa propriedade P aplicada á um x N – digamos P(x) –
vale para todo x N.
