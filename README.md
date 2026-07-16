<div align="center">

# ✊ Pedra, Papel e Tesoura

### Jogo clássico desenvolvido com HTML, CSS e JavaScript

<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">

</div>

---

## 📖 Sobre o projeto

O **Pedra, Papel e Tesoura** é uma versão digital do clássico jogo Jokenpô, desenvolvida para praticar lógica de programação, manipulação do DOM e interação com o usuário.

O jogador escolhe entre pedra, papel ou tesoura, enquanto a máquina realiza uma escolha aleatória. A aplicação compara as jogadas, informa o resultado da rodada e atualiza automaticamente o placar.

## 🎮 Como funciona

O jogador seleciona uma das três opções disponíveis:

- ✊ Pedra
- ✋ Papel
- ✌️ Tesoura

Após a escolha, o sistema gera uma jogada aleatória para a máquina e compara os resultados seguindo as regras tradicionais do jogo.

```text
Jogador escolhe uma opção
           ↓
Máquina gera uma escolha aleatória
           ↓
As jogadas são comparadas
           ↓
O resultado é exibido
           ↓
O placar é atualizado
```

## 🏆 Regras do jogo

| Jogada | Vence |
| --- | --- |
| Pedra | Tesoura |
| Papel | Pedra |
| Tesoura | Papel |

Quando o jogador e a máquina escolhem a mesma opção, a rodada termina em empate.

## ✨ Recursos principais

- Escolha entre pedra, papel e tesoura.
- Jogada aleatória da máquina.
- Comparação automática das jogadas.
- Exibição de vitória, derrota ou empate.
- Placar do jogador.
- Placar da máquina.
- Botões interativos.
- Interface colorida e intuitiva.
- Feedback visual ao passar o mouse sobre os botões.

## 🛠️ Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript
- DOM
- Google Fonts

## 🎯 Objetivo do projeto

Este projeto foi desenvolvido para praticar e demonstrar conhecimentos em:

- Lógica condicional.
- Funções em JavaScript.
- Manipulação do DOM.
- Eventos de clique.
- Geração de números aleatórios.
- Atualização dinâmica de elementos.
- Organização de constantes.
- Estruturação de interfaces com HTML.
- Estilização e interação com CSS.

## 🧠 Lógica da partida

As opções do jogo são organizadas em constantes:

```javascript
const GAME_OPTIONS = {
    ROCK: "rock",
    PAPER: "paper",
    SCISSORS: "scissors"
}
```

A escolha da máquina é definida aleatoriamente e comparada com a escolha do jogador para determinar o resultado da rodada.

## 🚧 Status

Projeto concluído, com possibilidade de futuras melhorias.

### Possíveis evoluções

- Botão para reiniciar o placar.
- Exibição da escolha da máquina.
- Animações durante as jogadas.
- Efeitos sonoros.
- Melhorias na responsividade.
- Modo melhor de três.
- Seleção de dificuldade.
- Histórico das partidas.
- Modo para dois jogadores.

---

<div align="center">

Desenvolvido por **Emanuel Penna**

</div>
