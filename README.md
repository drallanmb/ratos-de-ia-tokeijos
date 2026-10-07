# 🐀 Ratos de IA — Caça aos Tokeijos

Um jogo estilo *Snake* em pixel art, inspirado no [Ratos de IA](https://ratosdeia.com.br/): em vez de uma cobrinha, é um ratinho roxo que come **tokeijos**, e o que cresce é o **rabo**.

## Como jogar

Abre o `index.html` no navegador. É um arquivo só, sem build e sem dependências.

- **Mover:** setas ou `WASD` (no celular, deslizar o dedo)
- **Pausar:** `Espaço`, `Esc`, `P` ou o botão ⏸
- **Recomeçar:** `Enter` ou `R`
- **Som:** `M` ou o botão 🔊

Não bate nas paredes amarelas nem no teu próprio rabo.

## Pontuação

| Item | Efeito |
|---|---|
| 🧀 Tokeijo | +10 pontos (× multiplicador ativo) e o rabo cresce |
| OpenAI | +20 e **×2** por 10s (comum) |
| Gemini | +30 e **×3** por 10s (médio) |
| Claude | +50 e **×5** por 10s (raro) |

Os valores ficam na tabela `POWERUPS`, no começo do script.

## Feito com

HTML, CSS e Canvas puro. Os sons são sintetizados na hora com a Web Audio API, sem arquivos de áudio.
