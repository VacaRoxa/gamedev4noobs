# Exemplo: Ficha de Construção de Inimigo (Gameplay) - Aranha Gigante

## Informações Básicas
*   **Nome:** Aranha Gigante
*   **Tipo:** Inimigo Comum (Encontrado em áreas de teias e cavernas úmidas)
*   **Função/Papel no Jogo:** Inimigo de emboscada / Causador de status (Veneno)
*   **Nível/Dificuldade Sugerida:** Nível 1-3 (Áreas iniciais e intermediárias)

## Atributos Principais
*   **Pontos de Vida (HP):** 50
*   **Dano (Ataque):** 15 (Mordida)
*   **Defesa/Armadura:** 5
*   **Velocidade de Movimento:** 4 (rápida em linha reta, lenta ao virar)
*   **Velocidade de Ataque/Ação:** 1 ataque a cada 1.5 segundos
*   **Resistências:** Nenhuma
*   **Fraquezas:** Fogo (recebe 50% de dano extra de ataques de fogo)

## Habilidades (Ativas e Passivas)
*   **Habilidade 1 (Ativa): Mordida Venenosa**
    *   Descrição: Ataque corpo a corpo que aplica veneno.
    *   Efeito: Causa 15 de dano inicial + 5 de dano por segundo por 3 segundos (total de 15 de dano de veneno).
    *   Cooldown/Custo: N/A (ataque básico)
*   **Habilidade 2 (Passiva): Emboscada**
    *   Descrição: Permanece imóvel e invisível em teias até o jogador se aproximar.
    *   Efeito: Surpreende o jogador, garantindo o primeiro ataque.
    *   Cooldown/Custo: N/A

## Comportamento (para Inimigos/Chefes)
*   **Padrão de Ataque:**
    1.  Se o jogador estiver a curta distância: Mordida Venenosa.
    2.  Se o jogador estiver a média distância: Tenta fechar a distância rapidamente.
*   **Padrão de Movimento:**
    1.  Inicia invisível em teias.
    2.  Ao detectar o jogador (raio de 5m), corre rapidamente em linha reta para atacar.
    3.  Após atacar, pode recuar ligeiramente antes de atacar novamente.
*   **Gatilhos de Fase (para Chefes):** N/A
*   **Interações Especiais:** Pode ser queimada por ataques de fogo, causando dano extra e interrompendo seu ataque.

## Recompensas (para Inimigos/Chefes)
*   **XP:** 10
*   **Ouro/Recursos:** 5-10 Ouro, chance de 10% de deixar cair 1 Minério de Ferro.
*   **Itens Especiais/Loot:** Chance de 5% de deixar cair "Glândula de Veneno" (material de crafting).

## Notas de Design
*   Projetada para ser um inimigo de "surpresa" que ensina o jogador a prestar atenção ao ambiente.
*   O veneno é um desafio inicial que incentiva o uso de poções de cura ou aprimoramentos de resistência.
*   Sua fraqueza ao fogo incentiva o uso de habilidades elementais ou itens consumíveis.
