# Exemplo: Bag de Mecânicas/Armadilhas/Perigos - Jump & Loot: A Mina do Goblin

## Nome do Jogo/Sistema: Jump & Loot: A Mina do Goblin

## 1. Mecânicas de Gameplay (Reutilizáveis)
*   **Mecânica:** Wall Jump
    *   **Descrição:** Permite ao jogador pular de uma parede para outra, ou subir por paredes estreitas.
    *   **Exemplos de Uso:** Acessar áreas elevadas, atravessar poços largos, escalar chaminés.
    *   **Notas de Design:** Requer feedback visual (Glim "grudando" na parede) e sonoro. Pode ser usado para criar rotas alternativas ou segredos.
*   **Mecânica:** Dash Aéreo
    *   **Descrição:** Um rápido avanço horizontal no ar, consumindo uma carga.
    *   **Exemplos de Uso:** Atravessar vãos muito largos, desviar de projéteis inimigos, alcançar plataformas distantes.
    *   **Notas de Design:** Cargas limitadas (1 ou 2 por pulo), recarrega ao tocar o chão. Essencial para o "game feel" de agilidade.
*   **Mecânica:** Ataque Carregado
    *   **Descrição:** Segurar o botão de ataque carrega um golpe mais poderoso.
    *   **Exemplos de Uso:** Quebrar blocos mais resistentes, causar mais dano a inimigos blindados, abrir passagens secretas.
    *   **Notas de Design:** Feedback visual (brilho no personagem) e sonoro (som de carregamento). Deixa o jogador vulnerável durante o carregamento.

## 2. Armadilhas (Reutilizáveis)
*   **Armadilha:** Espinhos no Chão
    *   **Descrição:** Pontas afiadas que causam dano ao contato.
    *   **Efeito no Jogador:** Causa 10 de dano, empurra o jogador ligeiramente para trás.
    *   **Como Evitar/Desativar:** Pular sobre eles, usar invencibilidade temporária (após ser atingido), ou desativar um mecanismo próximo.
    *   **Notas de Design:** Usado para testar precisão de pulo. Pode ser combinado com inimigos para criar desafios de evasão.
*   **Armadilha:** Pedras Caindo
    *   **Descrição:** Pedras que caem do teto ao serem ativadas por um gatilho (jogador passando por baixo, alavanca).
    *   **Efeito no Jogador:** Causa 30 de dano, atordoa por 1 segundo.
    *   **Como Evitar/Desativar:** Correr rapidamente, usar dash, ativar e recuar, ou quebrar o suporte (se visível).
    *   **Notas de Design:** Usado para criar momentos de tensão e testar tempo de reação. Feedback visual (rachaduras no teto) e sonoro (som de desmoronamento) antes da queda.

## 3. Perigos Ambientais (Reutilizáveis)
*   **Perigo:** Gás Venenoso
    *   **Descrição:** Nuvens de gás verde que causam dano contínuo.
    *   **Efeito no Jogador:** Causa 5 de dano por segundo, aplica status "Envenenado" (reduz velocidade de movimento em 20%).
    *   **Como Interagir/Superar:** Atravessar rapidamente, usar poções de resistência a veneno, encontrar rotas alternativas, desativar a fonte do gás.
    *   **Notas de Design:** Usado para criar áreas de risco/recompensa ou para forçar o jogador a encontrar soluções criativas.
*   **Perigo:** Água Ácida
    *   **Descrição:** Poças de líquido corrosivo que causam dano ao contato.
    *   **Efeito no Jogador:** Causa 15 de dano por segundo ao contato.
    *   **Como Interagir/Superar:** Evitar o contato, usar plataformas flutuantes, ou ter resistência a ácido.
    *   **Notas de Design:** Usado para criar barreiras ou desafios de plataforma que exigem precisão.

## 4. Tipos de Inimigos (Comportamentos Genéricos)
*   **Tipo de Inimigo:** Patrulheiro Simples
    *   **Comportamento Principal:** Move-se em um padrão pré-definido (linha reta, círculo). Ataca ao contato ou ao ver o jogador.
    *   **Fraquezas Comuns:** Previsível, pode ser facilmente evitado ou emboscado.
    *   **Notas de Design:** Usado para introduzir combate básico e ensinar padrões de movimento.
*   **Tipo de Inimigo:** Emboscador
    *   **Comportamento Principal:** Permanece oculto (em teias, buracos, escuridão) e ataca quando o jogador se aproxima.
    *   **Fraquezas Comuns:** Vulnerável antes de iniciar o ataque, pode ser revelado por luz ou som.
    *   **Notas de Design:** Usado para criar sustos e testar a atenção do jogador ao ambiente.
*   **Tipo de Inimigo:** Atirador
    *   **Comportamento Principal:** Mantém distância e atira projéteis no jogador.
    *   **Fraquezas Comuns:** Vulnerável a ataques corpo a corpo, pode ser flanqueado.
    *   **Notas de Design:** Usado para criar desafios de evasão e forçar o jogador a usar cobertura ou fechar a distância rapidamente.
