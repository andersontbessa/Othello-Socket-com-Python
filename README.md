Implementação de Projeto de Sockets com Python, utilizando-se de cliente e servidor por meio de Sockets.


1) Objetivo: Implementar o Jogo Othello (Reversi) com Sockets
O Othello (Reversi) é disputado entre dois jogadores em um tabuleiro 8x8 com
64 discos que possui uma cor escura em um dos lados da face e no outro uma cor
clara, cujo o objetivo é ficar com mais peças da sua cor no tabuleiro ao final do jogo.
A partida começa com 4 peças no centro do tabuleiro, duas brancas e duas
pretas, sendo sempre as brancas na grande diagonal a1-h8.
O jogador com as pretas começa a partida colocando uma peça em uma das
Uma vez que um jogador faça uma jogada válida, todas as peças do oponente
que estejam em uma linha reta (horizontal, vertical ou diagonal) entre a peça recémcolocada e qualquer outra peça do jogador que fez o movimento são viradas e passam
a ser da cor deste jogador.
O jogo termina quando nenhum dos jogadores puder fazer movimentos (por
exemplo, quando todas as casas estiverem ocupadas ou todas as peças do tabuleiro
estiverem com a mesma cor virada para cima.
Se um jogador possuir mais peças que o adversário, ele vence. Se ambos os
jogadores tiverem a mesma quantidade de peças, o jogo termina em empate.

2) Funcionalidades Básicas
• Controle de turno, com definição de quem inicia a partida
• Movimentação de peças do tabuleiro
• Desistência
• Chat para comunicação durante toda a partida
• Detecção de vencedor
