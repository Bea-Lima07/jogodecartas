 Jogo de Cartas 21 (Blackjack Simplificado)

Aplicação web desenvolvida em **Java com Spring Boot**, que simula uma versão simplificada do jogo Blackjack (21), com foco em **lógica de jogo, controle de turnos e regras de negócio**.

---

 Visão Geral

O Jogo de Cartas 21 é um sistema onde múltiplos jogadores competem para atingir **exatamente 21 pontos** por meio da soma das cartas jogadas na mesa. Cada vez que um jogador alcança 21, ele marca um ponto e uma nova rodada é iniciada.

O vencedor é o jogador que acumular **mais pontos ao final da partida**.

---

 Funcionalidades

- Suporte a múltiplos jogadores (quantidade configurável)
- Distribuição automática de cartas
- Controle de turnos
- Jogadas condicionadas às regras do jogo
- Sistema de pontuação
- Reinício automático da rodada ao atingir ou ultrapassar 21
- Encerramento automático da partida

---

 Regras do Jogo (Resumo)

- Cada jogador inicia com **5 cartas** na mão.
- No seu turno, o jogador pode:
  - Jogar uma carta válida na mesa
  - Comprar uma carta (se não houver jogadas válidas)
  - Passar a vez (após comprar carta e não poder jogar)
- A soma das cartas da mesa:
  - **Não pode ultrapassar 21**
  - Ao atingir **21**, o jogador marca 1 ponto e a mesa é resetada
  - Ao ultrapassar **21**, a mesa é resetada sem pontuação
- O jogo termina quando:
  - Os jogadores ficam sem cartas **ou**
  - O baralho não possui cartas suficientes
- Vence quem obtiver **mais pontos**

Valores das Cartas
- Ás (A): 11 pontos (ou 1 ponto se ultrapassar 21)
- Figuras (K, Q, J): 10 pontos
- Cartas numéricas (2–10): valor nominal

---

 Tecnologias Utilizadas

- Java
- Spring Boot
- Thymeleaf
- HTML5
- CSS3
- JavaScript
- Docker (deploy)
- Render (hospedagem)

---

 Aplicação em Produção

🔗 **Link de acesso:**  

Para acessar o jogo, cole o link a seguir diretamento no navegador:
https://jogodecartas-dtux.onrender.com/

> Obs.: A aplicação está hospedada em plano gratuito e pode levar alguns segundos para iniciar no primeiro acesso.

---

 Contexto Acadêmico

Projeto desenvolvido com fins acadêmicos no curso de **Engenharia de Software**, com foco em:
- Programação Orientada a Objetos
- Lógica de negócio
- Arquitetura de aplicações web
- Integração entre backend e frontend

---

**Beatriz Rodrigues Lima**  
Estudante de Engenharia de Software  
🔗 GitHub: https://github.com/Bea-Lima07

