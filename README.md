# Helicopter

Jogo de física em [p5.js](https://p5js.org/) + [matter.js](https://brm.io/matter-js/): controle um helicóptero que precisa entregar um pacote sem cair no chão.

## Como jogar

Abra `index.html` no navegador — não precisa de instalação nem servidor.

- Segure o mouse/clique para o helicóptero subir, solte para descer
- O objetivo é manter o helicóptero no ar e entregar o pacote com segurança

## Estrutura

- `sketch.js` — física do voo (matter.js) e lógica do jogo
- `index.html` — carrega p5.js, matter.js, p5.play e o sketch
- `helicopter.png`, `package.png` — sprites

## Rodando localmente

Nenhuma dependência externa: as bibliotecas já estão incluídas no repositório. Basta abrir `index.html` direto no navegador ou servir a pasta com qualquer servidor estático (ex: `npx serve .`).
