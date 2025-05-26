# Jogo de Cartas 21 (Blackjack Simplificado)

Bem-vindo ao Jogo de Cartas 21, desenvolvido em Java com Spring Boot e Thymeleaf!

## 🎮 Sobre o Projeto

Este projeto simula um jogo de cartas online, onde os jogadores devem somar cartas na mesa até atingir **exatamente 21** pontos. O objetivo é ser o jogador que mais vezes atinge 21 antes do final do baralho.

## 🃏 Regras do Jogo

- O jogo permite de 2 a N jogadores (personalizável ao iniciar).
- Cada jogador recebe 5 cartas na mão no início.
- No seu turno, o jogador pode:
    - **Jogar uma carta** da mão (clicando sobre ela).
    - **Comprar carta** (apenas se não puder jogar nenhuma carta válida).
    - **Passar a vez** (só se não tiver mais jogadas possíveis E já tiver comprado uma carta no turno).
- As cartas são jogadas na **mesa central**, somando seus valores.
    - **A soma das cartas da mesa não pode ultrapassar 21**.
    - Se somar exatamente 21, o jogador ganha 1 ponto, a mesa é limpa e inicia uma nova rodada.
    - Se ultrapassar 21, a mesa é limpa e ninguém ganha ponto.
- O jogo termina quando:
    - Todos os jogadores ficam sem cartas na mão; **ou**
    - O baralho não tem cartas suficientes para nova rodada.
- Vence quem fizer **mais pontos** (quem mais vezes atingir 21).

### Valores das Cartas
- A = 11 pontos (ou 1 se ultrapassar 21)
- K, Q, J = 10 pontos
- 2-10 = valor nominal

## 🚀 Como Executar Localmente

1. **Clone este repositório:**
   ```bash
   git clone https://github.com/seu-usuario/jogodecartas.git
   cd jogodecartas

