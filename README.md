# PRO-C15-Group

1: dentro do setup(),  score = 0 e console.log("A pontuação é:" + score)
2: dentro do draw(),  text("Pontuação: " + score, 500,50) e console.log("A pontuação é: " + score)
3: score = score + frameCount/60;
4:if(gameState === 1){
    chao.velocityX = -6
  } else if(gameState === 0){
    chao.velocityX = 0;
  }

5: Ajustar recortand oe colando para dentro do if o que tem que acontecer só no play

# PRO C16

- 1. grupoObstaculos = createGroup(); e grupoNuvens = createGroup();
- 2. grupoObstaculos.add(obstaculo); e grupoNuvens.add(nuvem);
- 3. (grupoObstaculos.isTouching(trex)){gameState = end;}
- 4. grupoObstaculos.setVelocityXEach(0); grupoNuvens.setVelocityXEach(0);
- 5. continuar com a imagem de gameOver prox aula
