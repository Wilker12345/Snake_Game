# Snake_Game

GUIA PARA O USUÁRIO

INSTALAÇÃO DO JOGO
1. Baixar, em um mesmo diretório, os arquivos: "Snake_Game.c", "deque.c", "deque.h", "lista.c", "lista.h", "pilha_encadeada.c", "pilha_encadeada.h", "pilha_sequencial.c", "pilha_sequencial.h".
2. Compilar e rodar o arquivo "Snake_Game.c".

EXECUÇÃO DO JOGO
1. Para mover a cobra, use as teclas W (para cima), A (para a esquerda), S (para baixo), D (para a direita).
4. A cobra possui uma cabeça ('0') e um corpo, composto de várias partes ('M').
5. A pontuação é obtida ao ingerir as frutas (*).
6. Existem 1 poder que a cobra obtém comendo as frutas do campo e 3 poderes obtidos ao ingerir as letras 'W', 'X' e 'Y'; ao obter um poder, aperte 'U' para usá-lo e 'J' e 'K' para rodar os poderes da lista de obtidos para a esquerda e direita, respectivamente. A cobra consegue armazenar até 3 poderes de uma só vez.
   6.1: Poder de inversão da cabeça com a ponta da cauda: identificado como "W", ao usá-lo a cobra inverte sua cabeça com a sua cauda, invertendo assim seu movimento e saindo de situações delicadas.
   6.2: Poder de aumento de velocidade: identificado por "X", faz a velocidade da cobra aumentar drasticamente. Use com cuidado!
   6.3: Poder de redução de área de contato: identificado pela letra "Y", faz com que a cobra reduza seu corpo pela metade todavia mantendo sua pontuação atual, facilitando a obtenção de pontuações mais altas pelo jogador.
7. Uma barra de especial chamada "Barra Imortalidade" é carregada conforme se come as frutas. Quando ela fica cheia uma mensagem de "Pronto" aparece. Para usar essa habilidade especial pressione a tecla de espaco. O poder deixa a cobra imortal por um tempo.
8. A velocidade de jogo aumenta gradualmente.

CRÉDITOS

A hierarquia de bibliotecas Linux e Windows para que o correto funcionamento do jogo fosse garantido em ambos sistemas operacionais foi pensado por Matthew Vlietstra na versão 0.5 de seu projeto em 2010.

