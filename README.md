Trabalho desenvolvido no primeiro período do curso de Ciência da Computação na Puc Rio.
O objetivo era desenvolver 2 jogos entre as seguintes opções: Pedra Papel e tesoura, Forca, Calculadora(Ignore o fato que isto não é um jogo) e Jogo de adivinhação. Eu fui além, fiz os 4 jogos e um menu que os antecede.
Os jogos tinham os seguintes requisitos, acredito ter cumprido todos:

JOGO DA FORCA

PRINCIPAL (700XP)
- Condição de vitória: Acertar a palavra toda (100XP);
- Condição de derrota: Perder todos os membros/vidas (6 no total) (100XP);
- Ao começar o jogo uma palavra aleatória deve ser gerada com base em uma LISTA DE PALAVRAS (todas dentro de um mesmo tema) (100XP);
- A entrada do usuário deve ser validada, permitindo que ele digite SOMENTE LETRAS (200XP);
- A única exceção é para o caso do jogador chutar uma palavra inteira (100XP);
- O jogo deve poder ser reiniciado (100XP);

EXTRA (300XP)
- Tudo da forca, porém feito no PyGame, devendo ter interação com o teclado para entrada de dados.

-----------------------------------------------------------------------------------

PEDRA, PAPEL E TESOURA

PRINCIPAL (300XP)
- Condição de vitória e derrota: Pedra > Tesoura > Papel > Pedra (50XP);
- O jogador decide se ele joga pedra, papel ou tesoura (50XP);
- O computador gera um resultado aleatório (50XP);
- O jogo deve poder ser reiniciado (100XP);
- Deve haver uma pontuação para o jogador (50XP);

EXTRA (300XP)
- Criar o jogo com uma interface gráfica no PyGame, usando imagens (de mãos ou dos itens).

-----------------------------------------------------------------------------------

CALCULADORA

PRINCIPAL (300XP)
- Único que não é jogo, porém tem que funcionar como uma calculadora vagabunda (100XP);
- Portanto, ela deve ter uma memória da ÚLTIMA OPERAÇÃO FEITA (100XP);
- Exemplo: Se eu digito 5, depois X, depois 3, o resultado que aparece é 15;
- Se eu quiser usar esse 15, eu consigo, é só eu digitar +, e depois 4, para obter 19;
- Não operar com mais de dois operandos (100XP);

EXTRA (300XP)
- Fazer a calculadora usando PyGame, com interface parecida com aquelas calculadoras de celular, porém funcionando como na parte principal.

-----------------------------------------------------------------------------------

JOGO DE ADIVINHAÇÃO

PRINCIPAL (400XP)
- Implemente um jogo de adivinhação. O computador "escolhe" (gera aleatoriamente) um número entre 1 e 1023, e o usuário tenta adivinhar o número escolhido (100XP);
- Para cada tentativa do usuário, o programa deve exibir na tela (150XP):
  - O número -1, se o número gerado for menor do que o número fornecido pelo usuário;
  - O número 1, se o número gerado for maior do que o número fornecido pelo usuário;
  - O número 0, se o número gerado for igual ao fornecido pelo usuário. Neste caso, o programa deve exibir o número de tentativas usadas pelo usuário para acertar a escolha do computador de finalizar a execução;
- Implemente a variação do jogo na qual usuário e computador podem trocar de funções. O programa começa perguntando quem tentará adivinhar: o usuário ou o computador (150XP);
- Ou seja, usuário e computador podem trocar de funções;

EXTRA (300XP)
- Implementar o jogo no PyGame, com botões no lugar das opções 0, 1 e -1, ou indicadores visuais.
