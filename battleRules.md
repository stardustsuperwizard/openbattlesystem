# Battle Rules
## Summary
Baseline mechanics for building a table top warfare game played with dice in a turn based fashion.

## Playing Surface
### Game Boundaries
The playing surface shall have a clearly defined boundary (also called “board edge") to delineate between in play and out of play.  A squad may not move beyond the board edge. Any squads that move beyond the board edge are removed from play and may not return.

A boundary or “board edge” is considered a rally point. If a squad has a status of Fallback and reaches a board edge, the squad will stop movement and may choose to take a morale check. Upon successful completion of the morale check the squad status shall become Normal and the squad continue play as normal. Any remaining Fallback movement is forfeited.

### Terrain
The game board may have objects on it that represent battlefield terrain. terrain may have additional rules associated with it, but it is not required.

### Difficult Terrain
Any area designated as difficult terrain shall incur a penalty to Movement of half distance when a unit is moves through this area.

### Cover Protection
A unit that is partially obscured by a piece of terrain shall receive a bonus of +1 to the Combat Save or a value of 6 when no value is present.

## Models and Weapons
### Model
A model is a single entity that exists in the tabletop. Models have the following profile stats:

* Ranged Combat (RC)
* Close Combat (CC)
* Physical Toughnes (PT)
* Mental Toughness (MT)
* Hit Points (HP)
* Combat Save (CS)
* Movement (MV)

### Weapons
Weapons are tools and abilities used by models to perform combat actions against other models. Weapons have the following profile stats:

* Distance (Dst)
* Attacks (A)
* Strength (S)
* Save Modifier (SM)

## Squads
A squad is made up of one or more models that perform actions during phases of a turn.

### Movement through squads
Friendly squads may move through other friendly squads.

Squads may not move through opposing squads.

### Squad Cohesion
When a squad numbers two or more models it must maintain cohesion. Unit cohesion is achieved by ensuring that every model in the squad is no further than 2” from at least one other model in the squad, unless the squad is engaged in close combat. 

When a squad has at least one model that is more than 2” away from any other squad model and the squad is not in close combat with an enemy unit, the squad is no longer in cohesion and will be required to take a morale check in the morale check phase of the turn.

If the morale check is passed, the unit may continue with their turn as normal but must make take a standard movement to bring all models into cohesion.

### Squads as Defenders in Ranged Combat
Enemy units must target the entire squad and may not target individual squad members. When a Defending squad takes wounds, the defending player will allocate the wounds to individual model Hit Points.

### Squad Movement Types
#### Standard
Basic movement that is done during the Movement Phase of the player’s turn.
#### Assault
Charging movement that is done by an attacking squad to initiate Close Combat with a defending squad in the combat phase.
#### Fallback
Retreating movement that is done by squad that has failed a morale check.
#### Advance
Extra movement that is done by a squad that has been declared the winner of a close combat combat and the enemy squad has a status of Fallback.

### Squad Status
#### Normal
The squad has no changes to normal rules.

#### Advance
The squad may select one option:

* May make an advance move towards an enemy unit, to start Close Combat. If the unit’s movement results in one enemy model and one friendly model making physical contact, a new round of close combat is initiated. Additionally, if this defending unit has a status of “Fallback” the attacking unit make attempt to remove defending unit from the game:
    * Form a pool of D6, 1 for each Hit Point in the defending unit.
    * Attacker rolls dice from the pool and for each roll of a 6, one hit point is removed from the defending unit. No “to save” roll is permitted.
    * May make an advance move to anywhere else on the board. 
  
#### Fallback
Squad must use Fallback move to move towards the nearest Rally Point and may not take a Standard Move in Movement Phase.
 
In addition the following restrictions apply to the squad:
* Squad may not Assault.
* Squad may not use Counter Offensive in close combat.

### Morale
#### Morale Check
A morale check is conducted by rolling a D6 and comparing the result against the Mental Toughness attribute. A successful result is when the die roll is less than or equal to the Mental Toughness value, plus or minus any modifiers. 

#### Ranged Combat Morale Check
After a squad has lost wounds to Ranged Combat a morale check is required. There is a modifier to the die roll of +1 for each Hit Point lost from the squad.

#### Rally Point
When a squad with the status of fallback comes into contact with a rally point (such as a board edge), the squad will be permitted to take a morale check to remove the status of Fallback. The squad may make this morale check even if they have already taken and failed a morale check.

## Game round
A game round shall consist of each player taking a turn of play. A begins when the first player begins their turn and ends when the last player has completed their turn.

## Player Turns
A turn begins when the first player begins the turn phase. Once their turn is completed, the next player begins their turn. Play continues until all players have completed their turn.

### Turn Phases
Each player completes the following set of phases, in the following order, which will comprise 1 turn:

1. Morale Check Phase
2. Movement Phase
3. Combat Phase
    * Ranged Combat
    * Close Combat

* If 1 or more squads have a status other than "Normal” then they shall participate in the “Morale Check Phase”
* If 1 or more squads have the ability to perform a movement, then the squad may make an action in the “Movement Phase"
* If 1 or more squads have the ability to perform a Combat Attack, then they shall participate in the “Combat Phase" with the additional restrictions:
      * Ranged Combat, if the squad has a value for Ranged Combat then they may make a Ranged Attack.
      * Close Combat, if the squad has a value for Close Combat then they may make a Close Combat Attack.

A squad that does not have a combat value for Ranged Combat may still be attacked by an enemy squad in the Ranged Combat phase of an opponents turn.

A squad that does not have a combat value for Close Combat may still be attacked by an enemy squad in the Close Combat phase of an opponents turn.

## Morale Check Phase
Morale checks are required for a squad for any of the following reasons:
* Squad Cohesion is broken.
* Squad Status is Fallback

If any of the current players units are in the status of fallback, they may opt to take a Morale Check at this time to regroup.
  * Success: If the unit passes their morale check, squad status will be changed to normal the squad may continue on with the rest of the turn. 
  * Failure: If the unit has failed their morale check, then the squad status will remain the same and will act according to the rules of the squad status.

## Movement Phase
Each unit on the board makes a standard movement, plus or minus any modifiers.

## Combat Phase
### Combat Sequence
#### Summary
Regardless of which combat method is chosen, the sequence is the same. Roll the number of “to hit” dice equal to the weapon attack profile against the attacker’s appropriate combat profile, plus or minus any modifiers. The successful rolls become the attacker’s “to wound” pool which is which is rolled against the defender’s toughness profile, plus or minus any modifiers from the weapons strength profile or special abilities. Lastly, the attacker’s successful  “to wound” rolls becomes the defender’s “to save” pool. The defender rolls the pool against the defending unit’s Armor Save profile, plus or minus any modifiers from the attacker’s weapon’s Armor Penetration profile and/or special rules. Any failed rolls by the defender results in that unit taking a wound for each failed “to save” roll.

#### To Hit Rolls
Attacking unit selects a defending unit. Attacker rolls the number of D6 equal to the number of Attacks (A) in the weapon profile against the unit's combat attribute, ranged combat (RC) for shooting and close combat (CC) for melee. The unit must meet or beat the combat score (plus or minus any modifiers) with each D6. 
#### To Wound Rolls
All successful "to hit" rolls become the pool for "to wound" rolls. To Wound rolls are based on the attacker rolling against the defenders Physical Toughness (PT) applying any modifiers from the weapon’s strength and special abilities, if any.
#### To Save Rolls
All successful "to wound" rolls becomes the defenders pool for "Combat Save" rolls. The defender rolls the dice in the pool against their Combat Save (AS) value, applying any modifiers from the weapon’s Save Modifier (SM) and special abilities, if any.

### Ranged Combat
#### Line of Sight
Attacking squads must have a clear unobstructed line of sight to the defending squad. Friendly squads do not block line of sight. Opposing squads will block line of sight.

#### Select attacking squad
Attacker selects a squad to perform ranged combat. 

#### Select defending squad
Once the attacking squad has been selected, a defending squad is selected. 

#### Measuring distances and targets within defending squad
The at least 1 unit from the defending squad must be within the length of one attacking squad’s unit’s weapon’s distance to perform ranged combat. The only units that are eligible for attacking and defending are those units that are within the distance of the attacker’s weapon.

#### Resolve combat sequence
* Attacker makes “to hit” rolls
* Attacker makes “to wound” rolls
* Defender makes “to save” rolls

#### Defender checks morale
If the defending squad lost 1 or more Hit Points, it may be required to take a morale check.

### Close Combat
#### Declaring Close Combat Assault
If the length between the attacking squad and the defending squad is less than or equal to the length of the attackers Assault Movement value, then the attacking squad may initiate close combat with an enemy squad, now the defending squad. 

In order to successfully initiate close combat and create a combat scrum with the defending squad, at least 1 attacking squad model must touch at least 1 defending squad model.

So long as at least one attacker and one defender from each squad are touching, all squad models are considered to be in the combat scrum and engaged in close combat.

#### Defender Counter Offensive
Before attacking player moves the attacking squad into the defending squad, the defending squad is allowed to make a ranged combat attack with units in the squad that have a ranged combat score.

Any weapon with a distance value is eligible to be used, the defender does not need to check distance. If a weapon is used for ranged combat it may not also be used in Close Combat. Resolve a normal Ranged Combat Phase, if the attacking player ends this section with a status of fallback, the close combat is cancelled. Otherwise the attacker will continue the assault move.

#### Assault Move
Attacking player will now move the attacking squad towards the defending squad creating the combat scrum. Move each squad model up to the maximum assault distance attempting to touch 1 or more defender models.

#### Determine order of play
After the attacking unit is engaged with the defending unit, order of play is determined.
1. Attackers that assaulted shall roll first.
2. If neither side assaulted this turn (ex. A second turn of close combat), then a roll off with 1D6 shall be performed with the highest roll winning. The winner shall now be known as the attacker.

#### Select Attackers and Defenders
Once order of play has been established and each player knows when they are active, begin rolling for combat by selecting models within the combat  scrum.

Combat actions may only be performed between units that are physically touching . If a unit is touching multiple enemy units, that unit  may allocate the total combat attacks between the multiple enemy units as the player  sees fit.

#### Resolve Combat Sequence for Attacker
* Attacker makes “to hit” rolls
* Attacker makes “to wound” rolls
* Defender makes “to save” rolls

#### Resolve Combat Sequence for Defender
* Defender makes “to hit” rolls
* Defender makes “to wound” rolls
* Attacker makes “to save” rolls

#### Determine combat winner(s) and loser(s)
Tally up which side took more Hit Point losses (not just model physical models), the side with fewer loses is declared the winner. If multiple different players are involved in the combat, the players are ranked terms of who look fewer loses. If neither the attacker or defender won the combat, the result is a draw and both players may consolidate fighters or opt to fallback and advance.

#### Loser morale check or fallback
Once a winner has been declared, the loser must choose to either perform a fallback move or take a morale check for the unit/squad to stay in combat. If the unit/squad fails the morale check, the unit/squad must perform a fallback move.

#### Consolidate fighters or Fallback and Advance
##### Consolidate
If the loser passes their morale check and opts to stay in combat, the units may now perform a consolidation move of 3” per unit. Consolidation happens with each player taking a turn to move a single unit with the winner going first. If no player was declared the winner and loser, have a die roll off to determine who makes the first move. Units may disengage with other units and move around to a more advantageous position. 
##### Fallback and Advance
* Loser’s Fallback
    * If the loser failed the morale check or opted out of the morale check then the unit must make a fallback move.
* Winner’s Advance
    * After the combat loser has performed the winner may now make an advance move.
 
#### Ranged Combat in Close Combat
##### Squads inside the Combat Scrum
Squads in the combat scrum may not use Ranged Combat regardless whether the squad has units that are not touching enemy units.

##### Squads outside the Combat Scrum
Squads that are outside of a combat scrum may choose to use Ranged Combat on the combat scrum. To initiate Ranged Combat, attacking squad makes performs a standard Ranged Combat sequence stopping after the"to hit" roll has been made.

If the close combat scrum contains 1 or more friendly squads, the attacking player shall Roll all dice in the pool. On a roll of 4+ the hit is successfully applied to the enemy in the scrum and are placed in the enemy "to wound" pool. All failed rolls are placed in the friendly "to wound" pool. Otherwise, all successful "to hit" dice rolls will form the enemy hits pool.

Resolve each hit pool in the following manner:

* Using the pool of dice allocated for the enemy continue with the rest of the ranged combat sequence.
    * if there are 2 or more enemy squads in the combat scrum, the dice from the pool will be allocated as follows:
        1.  Select which squad will be the first squad, roll one die from the pool. 
        2. On a roll of a 4+ the hit is assigned to that squad. Otherwise continue to next enemy squad until a 4+ is rolled, going back to the original squad and repeating as necessary.
        3. Repeat this process with the each enemy squad until all dice from pool are allocated to an enemy squad, going back to the original squad and repeating as necessary.
        4. Once all "to wound" dice from the pool have been allocated to enemy squads continue with the normal ranged combat sequence.
   * If the enemy squad is required to take a morale check it will do so and follow instructions for result.
   * If a failed morale check causes the squad to change status and fallback out of combat and there are no other enemy squads in the combat scrum, close combat will end with friendly squad declared the winner.

If a friendly squad losses 1 or more Hit Points as a result of Ranged Combat it will be required to take a morale check and follow instructions for result. 

If the combat scrum is intact after the ranged combat then all Hit Points lost from Range Combat shall count towards determining which squad wins close combat.

# Formulas
## Combat
* To Hit
  * Ranged Combat
      * D6 + (positive modifiers) + (negative modifiers) >= Attacker’s Ranged Combat Score (RC)
  * Close Combat
      * D6 + (positive modifiers) + (negative modifiers) >= Attacker’s Close Combat Score (CC)
* To Wound
  * D6 + (Attacker’s Weapon’s Strength Score (S) ) + (positive modifiers) + (negative modifiers) >= Defenders’s Toughness Score (T)
* To Save
  * D6 - (Attacker’s Weapon’s Armor Penetration Score (AP) ) + (positive modifiers) + (negative modifiers) >= Defenders’s Armor Save Score (AS)
