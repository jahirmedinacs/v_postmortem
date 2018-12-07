___

# G12 Postmortem

* Jahir Gilberth Medina Lopez
    - **USP# :** *10659682*

* Nícolas Bassetto Leite
    - **USP# :** *8937292*

* Hermes Mac Kevin Cabanillas Encarnación
    - **USP# :** *10659953*

___


# Ultimate-Party-Fighting-Simulator

[Download it Here !](https://nicolasleite.itch.io/upfs "Ultimate Party Fighting Simulator
")

## Introdução

Quando começamos a planejar o jogo acreditamos que tudo daria certo mas, na realidade, nosso "acreditar" pouco importou.

Com a ideia de fazer um jogo bom, legal, empolgante, etc (que desse para jogar até no banheiro ou na sala se esquecendo de almoçar), nós começamos a idealizar os itens, escolher técnicas, mas o maior problema foi a inexperiência. É engraçado por que o desenvolvimento desse jogo resultou também no ganho de experiência que nunca tivemos.

<!--
### SSC0770, As Aulas certas para um pessoal inexperiente.

Durante as aulas recebidas, nós começamos a perceber que otimizar as mecânicas e o *gameplay* é ainda mais difícil que quer fazer um jogo visualmente atrativo; mais ainda, ao longo das aulas nós tínhamos confiança no projeto, 
-->

### Um Jogo é mais que ideias

Uma das ideias originais foi fazer um [**shoot'em up *tático***](http://hotlinemiami.com/ "Hotline Miami"), entre outras.
Após uma discussão entre os membros do grupo foi combinado fazer uma mudança de tipo de jogo.

A gente decidiu fazer **um jogo de luta**, um dos membros surgiu com essa ideia em um momento que a gente ainda tinha nem considerado o *cronograma de desenvolvimento*, mas a ideia foi tão legal e empolgante, que ninguém reparou nisso.

Uma coisa importante a detalhar é o desejo do *team* de quer fazer um jogo de luta, de **[*gameplay* frenético](https://www.adultswim.com/games/pc-console/duck-game/ "DuckGame") e [partidas curtas](http://nidhogggame.com/ "Nidhogg")**, mas foi um escopo de jogo fora de nossos limites.

Durante o tempo destinado ao desenvolvimento, nunca previmos tempos ociosos ou imprevistos que poderiam atrapalhar o mesmo, além de ter um jogo que precisava de mais *playtest* que qualquer outra coisa, ***a gente se focou em fazer experiência divertida mas somente funcional***, deixando a otimização das mecânicas ao final.



### Descrição da equipe

* **Douglas Talach** :
- Propôs a ideia de desenvolver um jogo de luta
- Estudante de Sistemas de Informação
- Abandonou a disciplina após um mês de aula

* **Mac Kevin** :
- Juntou-se à equipe após as 3 primeiras aulas
- Estudante de Ciências da Computação
- Tem experiência em desenvolvimento de jogos (from scratch , using C/C++ and OpenGL) 

* **Nícolas Leite** :
- Estudante de Ciências da Computação
- Pouca experiência em desenvolvimento de jogos
- Integrante da equipe desde o início 

* **Jahir Medina** :
- Membro da equipe desde o início, propôs a opcao desenvolver um jogo shoot'em up
- Estudante de Ciências da Computacao
- Tem experência como o [Source Engine](https://developer.valvesoftware.com/wiki/SDK_Docs 'Source SDK')


### Muitos Protótipos não funcionais

O método de desenvolvimento escolhido foi todos iniciarem o desenvolvimento de um protótipo e escolher o melhor, mas por causa disso, tudos ficamos confiando no trabalho do outro como um todo e nao como um trabalho compartilhiado.


## Desenvolvimento

### Cronograma de Desenvolvimento

Na tabela aqui abaixo, pode-se ver as metas propostas assim como as datas previstas e se foram cumpridas ou não.

| Start     |  End      | Activities                                            | Achieved   | At Time?  |
|:-----:    |:-----:    |------------------------------------------------------ |---------  |---------- |
| 07/10     | 13/10     | Arte do jogo, músicas                                 | No        | No        |
| 14/10     | 20/10     | Implementação de mecânicas - movimentos e interações  | Sim       | +10 Dias  |
| 21/10     | 27/10     | Implementação das mecânicas - modos de jogo           | Sim       | Sim       |
| 28/10     | 03/11     | Polimento das mecânicas e bug-fixes                   | No        | No        |
| 04/11     | 08/11     | Play-test e bug-fixes                                 | Sim       | +4 Dias   |
| 09/11     | 10/11     | Mostra de jogos                                       | No        | No        |
| 10/11     | 04/12     | Post mortem                                           | Sim       | Sim       |

#### Imprevistos

* aproximadamente após um mês do início das aulas, o membro Douglas , se retirou da disciplina, sem avisar os demais membros, nos deixando sem um membro, além de ser o **pai da ideia do jogo**.

* na 3ª semana de setembro o integrante Jahir Medina sofreu um acidente, machucando-se nas costas.

* quando foi o momento de fazer a arte e a musica, nós não tínhamos nem ideia de como fazê-las, portanto foi um tempo morto, onde além de procurar soluções, nós começamos também procurar outros tipos de jogos (tentativa de fuga das responsabilidades e dificuldade)

### O que deu certo?

1. Conseguir implementar o protótipo apesar da pressão
2. Achar o melhor engine que precisávamos para jogos de luta ([M.U.G.E.N.](http://www.elecbyte.com/mugendocs/mugen.html "M.U.G.E.N."))
3. Estudar a engine escolhida o suficiente para aprendê-la
4. Trabalhar em equipe, ainda fazendo de técnicas de desenvolvimento erradas.
5. Testar algumas mecânicas.

### O que poderia ter sido feito melhor?

1. Possuir mais conhecimento em desenho, animação e música
2. Não ter confiado muito nos prazos combinados
3. Conhecer os membros da equipe antes de formá-la
4. Utilizar um projeto pronto como base, sendo necessário apenas alterar e otimizar as mecânicas
5. Experiência prévia na área de desenvolvimento de jogos, principalmente no planejamento de projetos.

### As advertências não devem ser ignoradas

Durante a apresentações ao longo do curso, o pessoal da **F.O.G.** nos advertiu de que tentar fazer um jogo de luta, ainda sé fosse pequeno *(4 personagens e um cenário)* é uma das piores opções em termos de dificuldade de implementação.

Durante as penúltimas aulas, notamos que não teríamos tempo de de fazer o **playtest com os nossos amigos**, sendo o playtest , no caso de um jogo de luta, **o mais importante de tudo**.

Foi quando, entendemos de que quando ninguém tem experiência com um [engine](http://www.elecbyte.com/mugendocs/mugen.html "M.U.G.E.N.") , é importante se dedicar em fazer algo que gere a prática suficiente, conseguindo assim, fazer um jogo bom.

É certo que  a equipe trabalhou sem uma meta definida e muito provavelmente sem muita motivação nos momentos finais (dado os acontecimentos), mas manter um profissionalismo durante o desenvolvimento tinha que ser o primordial.

As aulas focadas em game design foram para a gente um *"o que estamos fazendo que não teríamos que ter feito"*, ter um foco e etapas para completá-las ajudam na subsequente otimização dessa parte.

Trabalhar sem uma metodologia de desenvolvimento pode ser critico, mas sé os membros do team não sé conhecem de antes, como no caso da gente, o gerenciamento foi deixado a votação geral, situação desaconselhável quando se têm um time de inexperientes.

## Conclusão

### Certo e Errado, um resumo final do desenvolvimento

O maior erro da gente foi acreditar que poderíamos ter feito um jogo de luta do zero sem ter experiencia, nem com o engine , nem com o tipo de jogo.

Um erro e acerto simultaneamente foi desconsiderar os tempos entre as etapas de desenvolvimento como tempos para continuar fazendo o jogo, por causa disso a os menores problemas(saída de um dos membros, ausência de outro) o cronograma deixou de funcionar, mas fazer isso também deixou tempo para lidar com o estresse de saber que o jogo escolhido seria difícil de fazer dado o tempo.

Mas o maior acerto foi ter feito isso com um grupo heterogêneo demais, onde cada quem tinha seus próprios focos e desejos para com o jogo, o pressão no momento de fazer um jogo difícil foi um motivador para continuar fazendo-o, a falta de profissionalismo por outro lado comprometeu.

### NaN / 10

Honestamente, o jogo final ficou um *lixo*, muito perto de uma pré-alfa, mas no caos deste desenvolvimento, aprendemos que importa mais ser *profissional* que ser bom ou ter tudo o tempo do mundo.

O jogo, com um 1% mais de nossa dedicação durante o semestre, poderia ter sido 100% melhor.

### Mas foi divertido ~~não~~ fazer o jogo, não é?

Copiar não é roubar se se aprende o suficiente com isso. Durante as aulas, o time pegou as melhores dicas, tentou consertar o jogo final o melhor possível para pelo menos conseguir fazê-lo funcional. Muitas partes do código são mudanças de código exemplo, mas isso é parte de aprender a trabalhar com um engine: entender o exemplo, modificar e se apropriar ele.
