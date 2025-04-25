# 🎮 Mini Jogo do Mario com JavaScript

Um jogo simples e divertido inspirado no Mario, feito com **HTML, CSS e JavaScript**, onde o jogador deve pular para evitar os obstáculos (canos). O jogo inclui som de início, som de game over, animações e controles por teclado ou toque.

## 🕹️ Funcionalidades

- 🏃 Animação do Mario correndo e pulando.
- 🧱 Obstáculo animado (cano).
- 🎧 Trilha sonora clássica do Mario.
- 💥 Detecção de colisão e tela de Game Over.
- 🔁 Reinício do jogo com tecla Enter.
- 🖱️ Suporte para teclado e dispositivos móveis (toque).

## 🔍 Como Funciona

- O Mario pula quando o jogador pressiona **espaço** ou toca na tela.
- Um loop detecta a posição do cano e do Mario para identificar colisões.
- Ao colidir, o jogo para, toca o som de derrota, exibe a tela de Game Over e permite reiniciar com **Enter**.
- O jogo começa ao clicar em **"Start"**.

## 📁 Estrutura do Código

- `startGame()`: Inicia o jogo e a música tema.
- `restartGame()`: Reinicia os elementos do jogo e toca a música novamente.
- `jump()`: Faz o Mario pular.
- `loop()`: Loop contínuo que detecta colisões a cada 10ms.
- Eventos de teclado e toque são usados para pular e reiniciar.

## 🧪 Tecnologias Utilizadas

- HTML5
- CSS3 (animações)
- JavaScript
- Áudios em MP3 e imagens em GIF/PNG

## 🚀 Como Usar

1. Clone ou baixe este repositório:
   ```bash
   git clone https://github.com/SofiaAraki/Mario-Jump.git
   ```
2. Abra o arquivo `index.html` em qualquer navegador moderno.
3. Clique em "Start" e divirta-se!

## 💡 Melhorias Futuras

- Adicionar contador de pontos ou tempo sobrevivido.
- Adicionar menu com níveis de dificuldade.
- Salvar recordes com `localStorage`.
- Incluir animação de pulo mais fluida.

---

> 🎨 Um ótimo projeto para quem está aprendendo lógica de programação, manipulação do DOM e eventos em JavaScript!
