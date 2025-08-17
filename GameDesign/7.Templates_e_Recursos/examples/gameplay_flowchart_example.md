# Exemplo: Fluxograma de Loop Central de Gameplay

Este fluxograma ilustra um loop central de gameplay simples, mostrando o ciclo de ações e recompensas que mantém o jogador engajado.

```mermaid
graph TD
    A[Início/Explorar Área] --> B{Encontrar Inimigo/Obstáculo?}
    B -- Sim --> C[Combater/Superar]
    C --> D[Obter Recompensa (Ouro/XP/Item)]
    D --> A
    B -- Não --> A
```

**Explicação:**
1.  **Início/Explorar Área:** O jogador começa explorando o ambiente do jogo.
2.  **Encontrar Inimigo/Obstáculo?:** O jogador encontra um desafio.
3.  **Combater/Superar:** O jogador engaja no desafio (combate, puzzle, plataforma).
4.  **Obter Recompensa:** Ao superar o desafio, o jogador é recompensado.
5.  **Voltar ao Início:** A recompensa motiva o jogador a continuar explorando e buscando novos desafios, reiniciando o loop.

---

# Exemplo: Fluxograma de Decisão Simples (Diálogo)

Este fluxograma mostra um exemplo de como as escolhas do jogador podem levar a diferentes resultados em um diálogo simples.

```mermaid
graph TD
    A[NPC: "Você pode me ajudar? Meu gato está preso na árvore!"] --> B{Escolha do Jogador}
    B -- "Sim, claro!" --> C[NPC: "Muito obrigado! Aqui está a recompensa."]
    C --> D[Fim da Interação]
    B -- "Não tenho tempo." --> E[NPC: "Que pena. Espero que alguém ajude."]
    E --> D
    B -- "Quanto você paga?" --> F[NPC: "Não é sobre dinheiro! É sobre o gato!"]
    F --> B
```

**Explicação:**
1.  **Início:** O NPC faz um pedido.
2.  **Escolha do Jogador:** O jogador tem três opções de resposta.
3.  **Caminho 1 (Sim):** Leva à aceitação da missão e recompensa.
4.  **Caminho 2 (Não):** Leva à recusa e ao fim da interação.
5.  **Caminho 3 (Negociar):** Leva a uma resposta negativa do NPC e retorna o jogador à escolha original, incentivando uma resposta mais altruísta ou encerrando a interação.
