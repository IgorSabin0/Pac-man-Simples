Pac-Man Arcade Mini
Jogo inspirado no clássico Pac-Man, desenvolvido com HTML, CSS e
JavaScript. O objetivo é coletar as pílulas do labirinto, evitar os
fantasmas e alcançar a maior pontuação.
🎮 Funcionalidades
- Movimentação pelas setas ou pelas teclas W, A, S e D.
- Pílulas comuns valem 10 pontos e especiais valem 50.
- Pílulas especiais permitem capturar fantasmas temporariamente.
- O jogador começa com 3 vidas.
- Recorde salvo no navegador.
- Pausa com a tecla Espaço.
- Controles na tela para dispositivos menores.
🛠️ Tecnologias
- HTML5: estrutura da página.
- CSS e Tailwind CSS: aparência da interface.
- JavaScript: regras, movimentação, pontuação e colisões.
- Canvas API: desenho do jogo.
- LocalStorage: salvamento do recorde.
- Font Awesome e Google Fonts: ícones e fonte retrô.
É necessária conexão com a internet para carregar as bibliotecas, os
ícones e a fonte externos.

▶️ Como executar
1. Baixe ou clone o repositório.
2. Abra o arquivo index.html em um navegador.
3. Clique em INICIAR JOGO e divirta-se.
Para clonar o projeto, use:
git clone https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git
🕹️ Como jogar
  Ação               Controle
  Mover              Setas ou W, A, S, D
  Pausar/continuar   Espaço

Colete todas as pílulas, fuja dos fantasmas e use as pílulas especiais
para capturá-los. Cada fantasma capturado vale 200 pontos.
🧠 Sobre o código
O labirinto é representado por uma matriz: 1 indica parede, 0 pílula
comum, 2 espaço vazio e 3 pílula especial. O JavaScript controla os
movimentos, os fantasmas, as colisões, as vidas e a pontuação. O desenho
é feito com Canvas, e o recorde fica salvo no navegador.
📁 Estrutura
pac-man-arcade-mini/
└── index.html
O HTML contém a estrutura, os estilos e o código JavaScript do jogo.
