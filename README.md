# Desafio Brasil Prev
## Descrição
<p align="left"> Projeto de desafio do Processo seletivo da Brasil Prev</p>

### 🛠 Sobre


<p>Considere o seguinte jogo hipotético muito semelhante a Banco Imobiliário, onde várias de suas mecânicas foram simplificadas. Numa partida desse jogo, os jogadores se alteram em rodadas, numa ordem definida aleatoriamente no começo da partida. Os jogadores sempre começam uma partida com saldo de 300 para cada um.</p>

<p>Nesse jogo, o tabuleiro é composto por 20 propriedades em sequência. Cada propriedade tem um custo de venda, um valor de aluguel, um proprietário caso já estejam compradas, e seguem uma determinada ordem no tabuleiro. Não é possível construir hotéis e nenhuma outra melhoria sobre as propriedades do tabuleiro, por simplicidade do problema.</p> 
<p>No começo da sua vez, o jogador joga um dado equiprovável de 6 faces que determina quantas espaços no tabuleiro o jogador vai andar
</p>

<ul>

<li>Ao cair em uma propriedade sem proprietário, o jogador pode escolher entre comprar ou não a
propriedade. Esse é a única forma pela qual uma propriedade pode ser comprada.</li>
<li>Ao cair em uma propriedade que tem proprietário, ele deve pagar ao proprietário o valor do aluguel da
propriedade.</li>
<li>Ao completar uma volta no tabuleiro, o jogador ganha 100 de saldo.</li>

</ul>

<p>Jogadores só podem comprar propriedades caso ela não tenha dono e o jogador tenha o dinheiro da venda.
Ao comprar uma propriedade, o jogador perde o dinheiro e ganha a posse da propriedade.</p>
<p>Cada um dos jogadores tem uma implementação de comportamento diferente, que dita as ações que eles
vão tomar ao longo do jogo. Mais detalhes sobre o comportamento serão explicados mais à frente.</p>
<p>Um jogador que fica com saldo negativo perde o jogo, e não joga mais. Perde suas propriedades e portanto podem ser compradas por qualquer outro jogador.</p>
<p>Termina quando restar somente um jogador com saldo positivo, a qualquer momento da partida. Esse jogador é declarado o vencedor.</p>
<p>Desejamos rodar uma simulação para decidir qual a melhor estratégia. Para isso, idealizamos uma partida
com 4 diferentes tipos de possíveis jogadores. Os comportamentos definidos são:</p>

<ul>
<li>O jogador um é impulsivo;
</li>
<li>O jogador dois é exigente;
</li>
<li>O jogador três é cauteloso;
</li>
<li>O jogador quatro é aleatório;
</li>
</ul>
<p>O jogador impulsivo compra qualquer propriedade sobre a qual ele parar.</p>
<p>O jogador exigente compra qualquer propriedade, desde que o valor do aluguel dela seja maior do que 50.</p>
<p>O jogador cauteloso compra qualquer propriedade desde que ele tenha uma reserva de 80 saldo sobrando
depois de realizada a compra.</p>
<p>O jogador aleatório compra a propriedade que ele parar em cima com probabilidade de 50%.</p>
<p>Caso o jogo demore muito, como é de costume em jogos dessa natureza, o jogo termina na milésima rodada com a vitória do jogador com mais saldo. O critério de desempate é a ordem de turno dos jogadores nesta
partida.</p>
<h2>Saída</h2>
<p>Uma execução do programa proposto deve rodar 300 simulações, imprimindo no console os dados referentes
às execuções. Esperamos encontrar nos dados as seguintes informações:</p>
<ul>
<li>Quantas partidas terminam por
time out (1000 rodadas);
</li>Quantos turnos em média demora uma partida;
<li>Qual a porcentagem de vitórias por comportamento dos jogadores;
</li>
<li>Qual o comportamento que mais vence.
</li>
<li>
</li>
</ul>
### 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- [Python](https://www.python.org/)
- [VS-code](https://code.visualstudio.com/)