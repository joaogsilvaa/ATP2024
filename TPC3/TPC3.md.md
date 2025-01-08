### TPC3

O trabalho consistiu no desenvolvimento de um programa em Python para o jogo dos 21 fósforos. O objetivo era implementar um jogo simples e interativo com dois modos de jogo.

No início do jogo, existem 21 fósforos disponíveis. Em cada turno, o jogador ou o computador pode retirar de 1 a 4 fósforos. Os jogadores jogam alternadamente, e o principal objetivo é evitar ser quem retira o último fósforo, pois esse jogador perde o jogo.

Na implementação, comecei por desenvolver uma função chamada tirar_fosforos, que define como cada jogador realiza a sua jogada. Quando o utilizador está a jogar, a função verifica se o número de fósforos retirados está dentro do intervalo permitido (entre 1 e 4) e se não excede o número de fósforos restantes. Caso contrário, o programa solicita que o utilizador insira outro valor válido. Para o computador, a lógica inclui uma estratégia que o permite garantir a vitória sempre que possível. Essa estratégia baseia-se na fórmula (fosforos - 1) % 5, que calcula o número de fósforos que o computador deve retirar para manter-se em vantagem.

Para controlar o fluxo do jogo, criei a função jogo, que gere os turnos entre o jogador humano e o computador. A função utiliza um loop que continua enquanto houver fósforos restantes. A cada iteração, exibe o número de fósforos disponíveis, chama a função tirar_fosforos para o jogador da vez, e atualiza o total de fósforos restantes. Caso o número de fósforos chegue a zero, o programa anuncia o perdedor (quem retirou o último fósforo) e o jogo termina.

Por fim, a função main permite ao utilizador selecionar o modo de jogo: se deseja começar primeiro ou deixar que o computador inicie. Dependendo da escolha, a função chama jogo com o parâmetro adequado (faz_computador_primeiro=True ou False).

A implementação foi bem-sucedida em atender aos requisitos do jogo, incluindo a garantia de que o computador sempre vence quando joga em segundo lugar e aproveita erros do utilizador caso jogue em primeiro. O código apresenta uma interface simples e funcional, proporcionando uma experiência fluida para o utilizador.