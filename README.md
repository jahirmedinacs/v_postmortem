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

Ao momento que a gente começa-se a planejar o jogo, tudo estava dando certo, mas , na realidade, o achar da gente importou muito pouco.

Com a ideia de fazer um jogo bom, legal, empolgante, etc (que de para jogar ate no banheiro o na sala deixando de almoçar), nos começámos a criar os item, escolher técnicas, mas o maior problema foi a inexperiência. É engraçado por que o fazer desse jogo implicou também ganhar experiência que nunca tivemos.

<!--
### SSC0770, As Aulas certas para um pessoal inexperiente.

Durante as aulas recebidas, nos começamos a perceber que otimizar as mecânicas e o *gameplay* é ainda mais difícil que quer fazer um jogo visualmente atrativo; mais ainda, ao longo das aulas nos tinhamos confianza no proyecto, 
-->

### Um Jogo é mais que ideias

Uma das ideas originals foi fazer um [**shut'en up *tactico***](http://hotlinemiami.com/ "Hotline Miami"), alem de outras mais
Após uma discuçâo emtre os membros do grupe foi combinado fazer uma mudança de tipo de jogo.

A gente combino fazer um **um jogo de luta**, um dos membros do feis essa recomendação em um momento que a gente ainda tinha nem considerado o *cronograma de desenvolvimento*, mas a ideia mesma foi tão legal, que ninguém reparo nisso.

Uma coisa importante a detalhar é o desejo do *team* de quer fazer um jogo de luta, de **[*gameplay* frenético](https://www.adultswim.com/games/pc-console/duck-game/ "DuckGame") e [partidas curtas](http://nidhogggame.com/ "Nidhogg")**, mas foi um escopo de jogo fora dos limites da gente.

Durante o tempo destinado ao desenvolvimento, nunca foram previstos tempos mortos ou imprevistos que poderiam atrapalhar o mesmo, além de ter um jogo que precisava de mais *gametest* que qualquer outra coisa, ***a gente se focou em fazer experiência divertida mas só no funcional***, deixando a otimização das mecânicas ao final.



### Descrição da equipe

* **Douglas Tchall** :
- Propor a idea de mudar a um jogo de luta, *viciado* nos jogos de luta.
- Estudante de Ingenieria dela informçao
- se retiro da materia apos das 4 primeras aulas.

* **Mac Kevin** :
- se unio ao team apos das 3 primeras aulas
- Estudante de Ciencias da Computacao
- Tem experenca fazendo jogos (from scratch , using C/C++ and OpenGL) 

* **Nicolas** :
- 

* **Jahir Medina** :
- Membro do team desde o comenco, propor a opcao de fazer um jogo shut'en up
- Estudante de Ciencias da Computacao
- Tem experenca como o [Source Engine](https://developer.valvesoftware.com/wiki/SDK_Docs 'Source SDK')


### Muitos Prototipos não funcionals

O metodo de desenvolvimento escolhido foi fazer tudos um prototipo e escolher o melhor, mas por causa disso, tudos ficamos confiando no trabalho do outro como um todo e nao como um trabalho compartilhiado.


## Desenvolvimento

### Cronograma de Desenvolvimento

nessa tabel aqui embaixo, podese ver as metas propostas assim tambem como as datas e si foram conseguidas ou nao.

| Start     |  End      | Atividades                                            | Archive   | At Time?  |
|:-----:    |:-----:    |------------------------------------------------------ |---------  |---------- |
| 07/10     | 13/10     | Arte do jogo, músicas                                 | No        | No        |
| 14/10     | 20/10     | Implementação de mecânicas - movimentos e interações  | Sim       | +10 Dias  |
| 21/10     | 27/10     | Implementação das mecânicas - modos de jogo           | Sim       | Sim       |
| 28/10     | 03/11     | Polimento das mecânicas e bug-fixes                   | No        | No        |
| 04/11     | 08/11     | Play-test e bug-fixes                                 | Sim       | +4 Dias   |
| 09/11     | 10/11     | Mostra de jogos                                       | No        | No        |
| 10/11     | 04/12     | Post mortem                                           | Sim       | Sim       |

#### Imprevistos

* aproximadamente na 4 semana apos do comenco das aulas, o membro Douglas , se retiro da materia, nos deixando sem um membro, alem de ser o **pae da idea do jogo**.

* na 3ra semana de setembro o integrante Jahir Medina sufrio um accidente, machucandose as costas.

* quando foi o momento de fazer a arte e a musica, nos nao tinhamos nem idea de como fazer elas, por tanto foi um tempo morto, onde alem de procurar solucoes, nos comensamos tambem a procurar outros tipos de jogos (tentativa de fuga das responsabilidades e dificultad)

### O que deu certo?

1. Coseguer fazer o prototipo alem da precao
2. Achar o melhor engine que a gente precisar ([M.U.G.E.N.](http://www.elecbyte.com/mugendocs/mugen.html "M.U.G.E.N."))
3. Mesher o suficiente com o engine escolhido como para ter experiência (grupal e individual) com ele
4. Trabalhar em equipe, ainda fazendo de tecnicas de desevolvimento erradas.
5. Poder Testar Mecanicas.

### O que poderia ter sido melhor?

1. Ter conhecimientos no desenho grafico , animacoes e musica
2. nao ter comfiado muito nos plazos de tempo combinados
3. ter conhecido de antes aos membro do team
4. fazer uso de um proyeto previo como baseamento, tendo so que otimizar as Mecanicas
5. ja tever experiência na area de desenvolvimento de jogos , especificamente no planejamento de proyectos deste tipo.

### As advertencias não são por que sim

Durante a apresentaçao do One Sheet, o pessoal da **F.O.G.** advitioce-nos de que tentar fazer um jogo de luta, ainda sé fose pequeno *(4 personagems e um cenario)* é umo das piores opçoes.

Durante as penúltimas aulas, a gente começo a achar que não tinhamos ter tempo para fazer nem o **gameteste com os amigos nossos** , sendo o gametest , no caso de um jogo de luta, **o mais importante de tudo**.

Foi quando, entendemos de que quando ninguém tem experiência meshendo com um [engine](http://www.elecbyte.com/mugendocs/mugen.html "M.U.G.E.N.")  es importante deixar tudo para começar fazer algo que gere a pratica suficiente, pudemdo assim, fazer um jogo bom.

é certo que o team trabalho sem uma meta definida e muito probabelmente sem motivaçao nos momentos finales (dado os aconteçemtos), mas manter um profissionalismo durate o desenvolvimento tinha que ser o primordial.

As aulas focadas em game desing foram para a gente um *"o que estamos fazendo que não teriamos que ter feito"*, ter um foco e etapas para completar elas ajudam na subsecuente otimizaçao dessa parte.

Trabalhar sem uma metodologia de desenvolvimento pode ser critico, mas sé os membros do team não sé conhecem de antes, como no caso da gente, o gerençamiento foi deixado a votaçao geral, situaçao desaconlheada quamdo se têm um team de inexperientes.

## Conclusão

### Certo e Errado, un resumo final do desenvolvimento

O maior erro da gente foi acreditar que poderiamos ter feito um jogo de luta sem ter experenca , nem com o engine , nem com o tipo de jogo.

Um erro y acerto em simultaneo foi desconsiderar os tiempos emtre as etapas de desevolvimento como tempos para continuar fazendo o jogo, por causa de isso a os menores problemas(saida de um dos membros, ausencia de outro) o cronograma deixo de funcar, mas fazer isso tambem deo tempo para lidiar com o estres de saber que o jogo escolhido seria dificl de fazer dado o tempo.

Mas o maior acerto foi ter feito isso com um grupe heterogeneo demais, onde cada quem tinha seus propios focos y desejos para com o jogo, o precao no momento de fazer um jogo dificil foi um motivador para continuar fazendo-lo, a falta de profissionalismo se tinha compromiso.

### NaN / 10

Honestamente, o jogo final ficou um *lixo* muito perto de uma pre-alpha, mas no caos deste desenvolvimento, foi aprendido que importa mas ser *profssional*que ser bom ou ter tudo o tempo do mundo.

O jogo, com um 1% mais de dedicaçao da gente , poderia ter sido 100% melhor.

### Mas foi divertido ~~não~~ fazer o jogo, ne?

Copiar não e robar se se aprende o suficiente com isso, durante as aulas, o team pego as melhores dicas, tento arrumar o jogo final o melhor possible para pelomenos conseguir rodar ele, muitas partes do codigo sao mudancas de codigo exemplo, mas isso e parte de aprender a trabalhar com um engine, entender o exemplo, mudar y se apropiar ele.
