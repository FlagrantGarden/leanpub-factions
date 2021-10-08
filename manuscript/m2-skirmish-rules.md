# Skirmish Rules {#skirmish-rules}

## Setup {#setup-rules}

1. Choose points total for each side (typically 24).
2. Set up terrain.
3. Roll or choose a scenario.
4. Roll for Captain’s trait (or use existing trait if an established character).
5. Players arrange themselves into two sides, as evenly as possible.
   Roll 1d6 each to determine which side will be attackers and which will be defenders: higher result is the attacker.
   Reroll ties.
   Unless otherwise specified in the scenario, the attackers take the first turn.
6. Deploy companies according to the scenario guidelines (each side with the same number of Company points).
7. Choose ambitions.
8. The active player takes their turn.

## General {#general-rules}

* Round down unless otherwise noted.
* Distance and Range are measured between the closest models in each Group.
* Facing doesn’t matter.
* Groups on the same side (attackers or defenders) are considered friendly.
  Groups on opposing sides are considered enemies.

## Terrain {#terrain-rules}

Difficult
: Each inch of movement through difficult terrain costs 2” of a model’s MO instead of 1”.

Obstacle
: If a model comes into base contact with an obstacle, it stops its Move for this activation (maintaining Cohesion).
If a model begins its Move in contact with an obstacle, it ignores the obstacle for the purposes of movement this activation.
If a model is within 3” of an obstacle, they count as being in Cover.

Cover
: Reroll all to-hit dice that hit against Groups on the opposite side of Cover.

Obscuring
: Groups cannot see past Obscuring terrain, or more than 3” into it.

Impassable
: Models cannot move through Impassable terrain.

{pagebreak}

## Turns {#turns}

The active side attempts to activate Groups until an activation is failed or they choose to end their turn.

At the beginning  of each turn, in order:

1. Rally Shaken Groups.
   All Shaken friendly Groups Test Resilience to remove Shaken status.
   If unsuccessful, the Group loses 1R and retreats; this does not end the turn.
   All Shaken friendly Groups must test to rally, but may do so in any order.
2. Make checks for Reckless Groups.
   If any friendly Group with the Reckless trait is within their movement range of an enemy, they must attempt to activate to Attack an enemy Group of your choice in range.
   If successful, Attack as normal; otherwise, they remain stationary, but this does not end the turn.

### Activation {#activation}

For each Group which did not Rally or check for Reckless:

1. Choose a Group to activate.
   Each Group may activate only once each turn.
2. Assign a valid order to the chosen Group (Move, Shoot, Attack, or any available special orders like Cast or Summon).
3. Roll 2d6, attempting to meet or exceed the Group’s minimum activation result for their given order.
   On a success, the Group performs the chosen order.
4. If the Group failed their activation test, end your side's turn and the next side's turn begins.
   Otherwise, choose another friendly Group to activate, or choose to end your turn.

{pagebreak}

## Moving {#move}

Move each model individually.
Models may not move through other models unless otherwise stated.

Cohesion
: At the end of a Move, all models in a Group must be within 3” of at least one other model in that Group, and must be at least 3” from enemy Groups (unless in melee with them).

## Shooting {#shoot}

If the activating Group has a MI profile, they may choose a Group within range that they can see to Shoot.

If Bloodied, roll 6d6 to hit; else roll 12d6.
Each die that shows a result equal to or higher than the Shooting Group’s MI value is a hit.
For each number of hits equal to the target’s T, reduce their R by 1.
If the target lost any R, it must Test Resilience.

## Attacking {#attacking}

If the activating Group has a ME profile, they may choose a target within their movement distance that they can see to Attack.

If already in melee, the Group may attempt to activate and either Attack or Retreat.

To Attack:

1. Move as many models as possible into base contact with the defending Group.
   * If the defending Group has the Defiant or Elusive traits, they may test to activate that trait.
     If successful, resolve their interrupting action; otherwise, they stand still and the attack continues as normal.
2. Both Groups try to hit each other, rolling 6d6 if Bloodied, else rolling 12d6.
   Each die that shows a result equal to or higher than the Group’s ME to-hit target for Attacking/Defending as appropriate is a hit (Shaken Groups only hit on a 6).
   For each number of hits equal to the enemy’s T, reduce the enemy’s R by 1.

## Retreating {#retreat}

A Group may activate to Retreat from melee or be forced to Retreat when failing while Testing Resilience.

The Group moves half their MO distance directly away from the cause of Retreat.
They may not pass within 3” of any enemy Groups.

If blocked by terrain or enemy Groups, roll 1d6 vs their current R; if lower, they lose R equal to the roll and stop moving.

If any member of the Retreating Group Retreats off of the table, the entire Group counts as having Routed and is removed from play.

{pagebreak}

## Testing Resilience {#testing-resilience}

Test for a specific Group immediately when they:

* Lose R.
* Are attempting to Rally.
* Become the last Group of their Company.

Test once for every remaining Group immediately when:

* The Captain's Group is Routed.
* The Company has lost Groups worth half or more of the total points fielded by their Company.

To Test Resilience:

1. Roll 2d6.
2. Modify the roll:
   * Subtract 1 from the result for each R lost (if testing due to lost R)
   * Subtract 1 from the result if the Group’s Company has less than half of their total points still in play
   * Add 1 to the result if the Captain’s Group is within 12”.
3. If the final result is equal to or higher than the Group’s R rating, they succeed.

If successful and Rallying, the Group is no longer Shaken.

If failed but the final result is greater than 0 the Group Retreats and becomes Shaken (if already Shaken, they lose 1 R instead).
If the final result is 0 or less, the Group is Routed.

## Shaken Groups {#shaken-Groups}

* Must Test Resilience to Rally at the beginning of next turn and may not activate for any other reason
* Only hit on a 6 in melee (not when Shooting)
* Lose 1R and Retreat when failing while Testing Resilience

If the Captain’s Group is Shaken, none of their special rules affect play.

## End of Game {#end-of-game}

When the chosen scenario's closing conditions are met, total VP according to the scenario guidelines to determine the winning side.
