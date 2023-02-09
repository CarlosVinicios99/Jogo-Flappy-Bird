# Jogo Flappy Bird

<p>
  Projeto do jogo Flappy Bird desenvolvido durante meus estudos de DOM, manipulação de HTML e interatividade de páginas com Javascript. O objetivo central do projeto foi justamente colocar em prática estes conceitos mencionados. 
</p>

## Visão Geral
<p>
  As barreiras são formadas por divs, cada barreira é formada por corpo e borda e pode ser invertida ou não, entre as divs existe um espaçamento, o local onde o espaçamento ocorre entre as divs ocorre de forma randômica, para isso foi utilizada a função Math.random().
</p>
<p>
  São 4 divs que ficam saindo e voltando para a janela do jogo, a animacao foi feita utilizando a funcao setInterval() a cada 20 milissegundos as barreias se deslocam horizontalmente por 3 pixels.
</p>

<p>
  O teste de colisão é realizado de forma simples comparando a posição (x, y) do pássaro com a posição (x, y) da barreira. Toda vez que o pássaro passa entre as barreiras ocorre o acréscimo de pontos no score.
</p>

## Jogo - Visual
<p>
  <img src="https://github.com/CarlosVinicios99/Jogo-Flappy-Bird/blob/main/imgs/jogo_flappy_bird.jpg?raw=true" alt = "visual do jogo">
</p>
<br>

## Jogo - Dinâmica 
<p>
  <img src="https://github.com/CarlosVinicios99/Jogo-Flappy-Bird/blob/main/imgs/flappy_bird.gif?raw=true" alt = "dinamica do jogo">
</p>
<br>


