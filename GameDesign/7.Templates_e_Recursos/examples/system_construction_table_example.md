# Exemplo: Sistema de Combate Básico e Tabela de Construção

Este exemplo ilustra como um sistema de combate simples pode ser definido e como seus dados podem ser estruturados em uma tabela.

## Sistema de Combate: Corpo a Corpo Básico

**Objetivo:** Permitir que o jogador e os inimigos troquem golpes, com base em atributos de Dano, Defesa e Pontos de Vida.

**Mecânicas Chave:**
*   **Ataque Básico:** Causa dano ao alvo.
*   **Defesa:** Reduz o dano recebido.
*   **Pontos de Vida (HP):** Determina a durabilidade de uma unidade.

**Fluxo Básico de Combate:**
1.  Atacante inicia um ataque.
2.  Dano base do atacante é calculado.
3.  Defesa do defensor é subtraída do dano.
4.  Dano final é aplicado aos Pontos de Vida do defensor.
5.  Se HP <= 0, defensor é derrotado.

## Tabela de Construção de Atributos de Combate (Exemplo para Jump & Loot)

Esta tabela mostra como os atributos de combate para diferentes entidades (jogador, inimigos) podem ser organizados e balanceados.

| Entidade        | Tipo         | Nível | HP Base | Dano Base | Defesa Base | Velocidade de Ataque (por seg) | Notas de Balanceamento                               |
|-----------------|--------------|-------|---------|-----------|-------------|--------------------------------|------------------------------------------------------|
| Glim (Jogador)  | Protagonista | 1     | 100     | 10        | 0           | 1.0                            | Ponto de partida para o jogador.                     |
| Aranha Gigante  | Inimigo Comum| 1     | 50      | 15        | 5           | 0.67 (1 ataque a cada 1.5s)    | Menos HP que o jogador, mas mais dano e defesa inicial. |
| Morcego Gigante | Inimigo Comum| 1     | 30      | 10        | 0           | 1.0                            | Frágil, mas rápido e pode voar.                      |
| Golem de Pedra  | Chefe        | 5     | 500     | 30        | 20          | 0.5 (1 ataque a cada 2s)       | Alto HP e Defesa, ataques lentos mas poderosos.      |

**Cálculo de Dano (Exemplo Simples):**
`Dano Final = Dano Base do Atacante - Defesa Base do Defensor`

**Considerações de Balanceamento:**
*   **Time-to-Kill (TTK):** Quanto tempo leva para o jogador derrotar um inimigo, e vice-versa. Ajustar HP, Dano e Defesa para que os combates sejam desafiadores, mas não muito longos ou muito curtos.
*   **Progressão:** Inimigos de níveis mais altos terão HP, Dano e Defesa maiores, exigindo que o jogador aprimore seu equipamento e habilidades.
*   **Variação:** Diferentes tipos de inimigos (tanque, DPS, suporte) exigirão diferentes estratégias de combate do jogador.
