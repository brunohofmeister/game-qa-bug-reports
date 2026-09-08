[🇧🇷 Ler este Bug Report em Português](Call_of_Duty_MW2_2022-pt.md)

# [Call of Duty MW2 2022] Visual bug causing enemy corpses to clip through map geometry (Clipping)

## Game Description
Call of Duty: Modern Warfare II (2022) is a first-person shooter (FPS) game focused on tactical military combat.

## Severity / Priority
* **Severity:** Low (Purely a visual glitch affecting enemy ragdolls, with no impact on mission progression).
* **Priority:** Low (Does not hinder core gameplay and has minimal effect on overall user experience).

## Test Environment
* **Platform:** PC (Steam / Battle.net).
* **Version/Year:** Updated build (July/2026).
* **Game Mode:** Campaign Mode / Mission 9 (Recon by Fire).

## Prerequisites
* Select the **Veteran** difficulty level.
* Progress to Mission 9 in Campaign mode.

## Steps to Reproduce
1. Start Mission 9 in Campaign mode.
2. Follow the friendly NPC's instructions until reaching the warehouse area.
3. Use the sniper rifle to eliminate enemies from a distance until ordered to breach the 3 warehouses.
4. Approach any warehouse, climb onto the roof, and throw a tear gas grenade down the chimney.
5. Eliminate most enemies inside, leaving only 1 alive.
6. Allow the last enemy to kill the player to force a checkpoint reload.
7. Observe the ragdoll position of the previously eliminated enemies upon respawning.

## Expected Result
Upon reloading the checkpoint, previously killed enemy corpses should either be cleared from the scene or correctly rendered with proper floor collision physics.

## Actual Result
Upon checkpoint reload, enemy corpses appear stuck or clipping through the map geometry (environment clipping), giving the appearance of falling through or being "swallowed" by the floor and walls.

## Evidence
![Enemies clipping through the environment in COD MW2](../imagens/codmw2_2022.png)
