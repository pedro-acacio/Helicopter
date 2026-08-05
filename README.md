# Helicopter

Jogo de física em [p5.js](https://p5js.org/) + [matter.js](https://brm.io/matter-js/): mova um helicóptero carregando um pacote e solte-o no momento certo para acertar uma caixa alvo no chão.

## Como jogar

Abra `index.html` no navegador — não precisa de instalação nem servidor.

- Seta esquerda / seta direita: move o helicóptero (e o pacote, que ainda está preso a ele) horizontalmente
- Seta para baixo: solta o pacote, que passa a cair sob física do matter.js (gravidade e colisão)
- O objetivo é soltar o pacote na hora certa para que caia dentro da caixa vermelha desenhada no chão

## Estrutura

- `sketch.js` — física do voo (matter.js) e lógica do jogo
- `index.html` — carrega p5.js, matter.js, p5.play e o sketch
- `helicopter.png`, `package.png` — sprites

## Rodando localmente

Nenhuma dependência externa: as bibliotecas já estão incluídas no repositório. Basta abrir `index.html` direto no navegador ou servir a pasta com qualquer servidor estático (ex: `npx serve .`).
