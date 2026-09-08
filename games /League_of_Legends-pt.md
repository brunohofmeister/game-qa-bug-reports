[🇺🇸 Read this Bug Report in English](League_of_Legends-en.md)

# [League of Legends] Exploit da Lâmina da Fúria de Guinsoo permite acúmulo infinito de status passivos (Infinite Stacking)

## Descrição do Jogo
League of Legends é um jogo multiplayer online battle arena (MOBA) de estratégia em tempo real focado em confrontos de equipes.

## Severidade / Prioridade
* **Severidade:** Crítica (Gera acúmulo infinito de velocidade de ataque e poder de habilidade, desequilibrando completamente as estatísticas dos campeões e a integridade competitiva da partida).
* **Prioridade:** Muito Alta (Permite que qualquer jogador com o item no inventário explore o bug para obter uma vantagem abusiva e garantida).

## Ambiente de Teste
* **Plataforma:** PC (Windows)
* **Versão/Ano:** Patch 4.20 / Encontrado em 2014.
* **Modo de Jogo:** Todos os modos (Summoner's Rift, ARAM, Custom).

## Pré-requisitos
* Selecionar um campeão focado em velocidade de ataque ou dano híbrido (ex: Kayle, Master Yi).
* Acumular ouro suficiente na partida para adquirir o item **Lâmina da Fúria de Guinsoo**.

## Passo a Passo para Reprodução
1. Inicie uma partida em qualquer modo de jogo.
2. Adquira a Lâmina da Fúria de Guinsoo na loja do jogo.
3. Ataque tropas, monstros neutros ou campeões inimigos sequencialmente para gerar os acúmulos (*stacks*) do item.
4. Continue desferindo ataques básicos continuamente mesmo após atingir o limite máximo previsto da passiva.

## Resultado Esperado
O efeito passivo da Lâmina da Fúria de Guinsoo deve acumular seus bônus de Velocidade de Ataque e Poder de Habilidade até o limite máximo de 8 *stacks*, mantendo o valor estático até o encerramento do combate.

## Resultado Atual
A passiva do item ignora o limite máximo e continua acumulando bônus de velocidade de ataque e dano infinitamente a cada golpe efetuado, concedendo valores desproporcionais ao campeão.

## Evidências
![Lâmina de Guinsoo acumulando status infinitamente](../imagens/lol_guinsoo.png)
