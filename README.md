# 🎮 Detona Ralph

Projeto desenvolvido durante o **Bootcamp de Front-end da DIO**.

## 📋 Sobre o projeto

Jogo inspirado no personagem Ralph, onde o objetivo é clicar no Ralph que aparece aleatoriamente nas janelas do painel antes que o tempo acabe.

## 🕹️ Como jogar

- O jogo começa automaticamente com **60 segundos** de tempo
- O Ralph aparece aleatoriamente em uma das **9 janelas** do painel
- Clique no Ralph para marcar pontos
- Ao fim do tempo, o jogo exibe sua pontuação final

## 🛠️ Tecnologias utilizadas

- **HTML5**
- **CSS3**
- **JavaScript**
- Google Fonts — *Press Start 2P*

## 📁 Estrutura do projeto

```
├── index.html
└── src/
    ├── audios/
    ├── images/
    │   ├── ralph.png
    │   ├── player.png
    │   └── wall.png
    └── scripts/
    │   └── engine.js
    └── styles/
        ├── main.css
        └── reset.css
```

## ⚙️ Funcionalidades

- Painel 3x3 com janelas clicáveis
- Aparição aleatória do inimigo a cada 1 segundo
- Contador de tempo regressivo (60 segundos)
- Placar de pontuação em tempo real
- Efeito sonoro ao acertar o Ralph
- Alerta com resultado final ao término do jogo