[🇺🇸 Read this Bug Report in English](Pimbolas-en.md)

# [Pimbolas] Bonecos da linha de defesa desaparecem após marcar gol utilizando o Super Chute

## Descrição do Jogo
Pimbolas é um jogo arcade de pebolim/futebol de mesa com mecânicas de superpoderes, lançado em 2026.

## Severidade / Prioridade
* **Severidade:** Média (Interrompe o fluxo normal da partida, impedindo a defesa adequada e exigindo a reinicialização da partida).
* **Prioridade:** Média (Gera desvantagem injusta na jogabilidade, embora a taxa de reprodução ainda seja inconsistente).

## Status

🔴 **Não corrigido**

## Ambiente de Teste
* **Plataforma:** PC (Windows 11)
* **Versão/Ano:** Build original de lançamento (2026).
* **Modo de Jogo:** Encontrado em uma partida personalizada no mapa de grama clássico.

## Pré-requisitos
* Selecionar o personagem **Frôr** para o jogador e **Peixe** para a CPU.
* Configurar os poderes da partida mantendo apenas a **Luva de Goleiro** habilitada.

## Passo a Passo para Reprodução
1. Inicie uma Partida Personalizada no mapa *Grama Clássico*.
2. Carregue a barra de habilidade do Super Chute.
3. Execute o Super Chute em direção ao gol adversário e marque o ponto.
4. Observe o reposicionamento dos bonecos na mesa após o reset da jogada.

## Resultado Esperado
Após a marcação do gol, todos os bonecos da linha de defesa e do meio-campo devem reaparecer (*respawn*) em suas posições originais da mesa para o início da próxima rodada.

## Resultado Atual
Em ocasiões esporádicas após a animação do Super Chute, os bonecos da linha de defesa desaparecem do campo (falha de renderização/despawn), deixando a área sem colisão e impossibilitando a defesa durante o restante da partida.

## Evidências
![Bonecos da defesa ausentes na mesa de Pimbolas](../imagens/pimbolas.png)
