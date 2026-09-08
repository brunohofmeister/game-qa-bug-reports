[🇧🇷 Ler este Bug Report em Português](League_of_Legends-pt.md)

# [League of Legends] Guinsoo's Rageblade exploit allows infinite passive stat stacking (Infinite Stacking)

## Game Description
League of Legends is a multiplayer online battle arena (MOBA) real-time strategy game focused on team combat.

## Severity / Priority
* **Severity:** Critical (Grants infinite Attack Speed and Ability Power stacking, completely breaking champion balance and competitive match integrity).
* **Priority:** Very High (Allows any player holding the item in their inventory to exploit the bug for an abusive, guaranteed advantage).

## Test Environment
* **Platform:** PC (Windows).
* **Version/Year:** Patch 4.20 / Found in 2014.
* **Game Mode:** All Modes (Summoner's Rift, ARAM, Custom).

## Prerequisites
* Select a champion focused on attack speed or hybrid damage (e.g., Kayle, Master Yi).
* Accumulate enough gold during the match to purchase the **Guinsoo's Rageblade** item.

## Steps to Reproduce
1. Start a match in any game mode.
2. Purchase Guinsoo's Rageblade from the in-game shop.
3. Attack minions, neutral monsters, or enemy champions sequentially to build item stacks.
4. Continue landing basic attacks continuously even after reaching the intended maximum passive limit.

## Expected Result
Guinsoo's Rageblade passive effect should stack its Attack Speed and Ability Power bonuses up to a maximum cap of 8 stacks, remaining static until combat ends.

## Actual Result
The item's passive ignores the maximum stats cap and continues to infinitely stack attack speed and damage bonuses with every hit, granting disproportionate values to the champion.

## Evidence
![Guinsoo's Rageblade infinitely stacking stats](../imagens/lol_guinsoo.png)
