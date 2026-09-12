[🇧🇷 Ler este Bug Report em Português](Speedy_Eggbert-pt.md)

# [Speedy Eggbert] Collision glitch allows clipping through pushable blocks using the skateboard (Collision Clipping)

## Game Description
Speedy Eggbert is an isometric 3D platformer and puzzle game originally released in 1998.

## Severity / Priority
* **Severity:** Low (Allows bypassing obstacles improperly by exploiting overlapping collision boxes).
* **Priority:** Low (Impacts natural progression in a few official levels and custom scenarios created in the map editor).

## Status

🔴 **Not Fixed**

## Test Environment
* **Platform:** PC (Windows).
* **Version/Year:** Found in 2012 (Likely present since launch in 1998).
* **Game Mode:** Custom Levels / Level Editor.

## Prerequisites
* Be in a level that contains at least 1 Skateboard and pushable/movable blocks.

## Steps to Reproduce
1. During gameplay, locate and ride the Skateboard vehicle.
2. Position the character riding the Skateboard right next to a pushable block.
3. Dismount the Skateboard on that exact spot.
4. Pull the block so that it moves directly on top of the spot where the Skateboard was left.
5. Walk the character directly into the block that is overlapping the Skateboard.

## Expected Result
The game's physics system should keep the block's collision box (hitbox) active, preventing character movement and blocking the path until the obstacle is moved to an open tile.

## Resultado Atual
Upon forcing movement against the block positioned over the Skateboard, a collision detection failure occurs (clipping), causing the character to instantly pass through the pushable block.

## Evidence
![Speedy Eggbert Skateboard and Blocks](../imagens/speedy_eggbert.png)
