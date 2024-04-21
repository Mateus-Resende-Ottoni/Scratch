
Relatório do Projeto: "Boss Rush"

Introdução:
O jogo "Boss Rush" foi desenvolvido como parte do projeto final em Scratch para demonstrar minhas habilidades em programação e design de jogos durante a minha graduação em Ciências da Computação na PUC Minas. Este relatório descreve o processo de criação do jogo, os elementos utilizados, a motivação por trás das escolhas feitas e como o jogo funciona.



1. Descrição do Jogo:
"Boss Rush" é um jogo de ação inspirado também em jogos do gênero Souls-like em que o jogador controla um espadachim enfrentando chefões em 5 níveis. A principal mecânica do jogo envolve desviar dos ataques dos chefões e os atacar.



2. Elementos Utilizados:

Movimentos: Usei os blocos de movimento para controlar a movimentação dinâmica do personagem em 8 direções e os ataques por esse realizados. Fora do controle do jogador, há também uso essencial dos blocos de movimentos nos padrões de movimentos para os chefões (cada qual possui um único com diferentes movimentos) e no movimento das magias utlizados pelo 5º chefão.

Aparências: Criei diferentes sprites para as diferentes seções dos menus, as dicas providas na tela de 'Game Over' o personagem principal, o efeito de corte e da explosão, o coração indicativo da vida, as caixas de diálogos entre os personagens e os cenários. Os sprites de estrela e raio utlizados pelo 5 chefão são provenientes da própria biblioteca do Scratch. Os sprites para os chefões foram todos obtidos do site 2 Minute Tabletop (https://2minutetabletop.com/). O sprite de corpo inteiro utilizado para o mentor é proveniente do jogo Jump Ultimate Stars, mais especificamente o utlizado pelo personagem Ichigo Kurosaki.

Sons: Adicionei sons da biblioteca disponível no Scratch para o ataque do personagem e sons para quando ambos chefões e o personagem são acertados pelo outro, com sons diferentes em acordo com cada, a fim de tornar o jogo mais imersivo. Adicionalmente, inseri a trilha sonora 'The Lava Dwellers' do jogo Stardew Valley (https://soundcloud.com/concernedape/the-lava-dwellers).

Eventos: Utilizei eventos em maneiras diversas, mas foram utlizados principalmente para detectar a mudança de cenários (Ex.: A mudança de cenário para o de cada chefão ativa seu respectivo comando de movimento), para sincronizar ações entre atores diferentes através da transmissão de mensagens (Ex.: O fim do jogo ao o jogador ficar com a vida abaixo de 1 é sincronizado dentre os diversos atores através da mensagem 'Game Over') e na cena final para detectar a escolha do jogador no diálogo (Os sprites da escolha detectam se foram clicados para transitirem uma mensagem).

Controle: Os controles do jogo são essencialmente simples, podendo o jogador se mover através das teclas 'W', 'A', 'S' e 'D', que rotaciona o personagem nessa direção e o impulsiona, e atacar pressionando a tecla de espaço. Quanto ao movimento, esse pode ocorrer tanto reto quanto em linhas diagonais (possibilitando 8 direções), a partir do momento que a rotação é gradual, podendo assim duas teclas de movimento serem pressionadas ao mesmo tempo para manter o personagem em um sentido diagonal, mas com a velocidade sendo diminuída para esse caso.

Variáveis: Utilizei para esse projeto um total de 18 variáveis. Dos usos mais notáveis, vale citar:
- Determinar a vida total do jogador;
- Determinar a vida total de cada chefão (e de seus clones, para o caso do 4º chefão);
- Impor um mínimo intervalo de tempo para a utilização consecutiva de ataques;
- Contar a quantidade de vezes que o jogador perdeu (utilizado para a determinação de uma variação de diálogo após vencer os chefões);
- Determinar para o 5º chefão qual dos 9 possíveis locais ele irá teleportar;
- Servir como mecanismo de reconhecimento para evitar que o chefão possa danificar o jogador enquanto ainda está aparecendo;

Operadores: Utilizei operadores principalmente em duas formas distintas: alterar valores e determinar relações lógicas. Para o primeiro caso, um uso notável está na movimentação do personagem, que utlizando de substraçõe e adições, altera o valor da direção do personagem para orientar sua rotação, e para esse mesmo exemplo há uma mostra do segundo caso, em que há em determinados valores da direção uma orientação automática, detectada por relações de 'menor que' e 'maior que'.



3. Motivação:
Minha principal motivação para criar "Boss Adventures" foi desenvolver uma divertida experiência em um jogo desafiador que incentive ao jogador aprender os padrões de movimentos dos inimigos para conseguir vencê-los. Além do mais, tive incentivo em buscar desenvolver visuais atrativos, pelo personagem do jogador ser uma criação minha.



4. Funcionamento do Jogo:
Após pressionar o botão de 'Start', o jogador é posicionado próximo ao centro da tela, e brevemente o primeiro chefão tem seu aparecimento indicado pouco acima de onde está o personagem. A partir desse momento, o objetivo do jogador é atacar o chefão com seu ataque pressionando a tecla de espaço e evitar seus ataques se movimento pelo mapa, caso contrário sofrendo dano. Há um indicativo visual do dano sofrido pelo personagem no canto superior direito da tela, com um sprite de coração que se altera a medida qe o dano é maior. Para o caso de o dano total exceder a quantidade de vida do personagem, o jogador recebe a tela de 'Game Over', onde uma dica é oferecida na figura de um conselho do mestre do personagem, podendo o jogador retornar ao menu de onde pode tentar novamente. Para o caso de o jogador conseguir vencer todos os 5 chefões, para ele aparece a tela de vitória, onde há um breve diálogo entre o personagem e o seu mestre.



5. Conclusão:
…
