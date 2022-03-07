# Characters and Gear
How to build an unit for a squad.

## Base Unit
### Initial Values
|Attribute    | RC | CC | T   | HP  | M   | Point Cost |
|:-:          |:-: |:-: |:-:  |:-:  |:-:  | :-:        |
|Initial Value| 0  | 0  | 2+  | 1   | 0   | 1          |

Unit is armed with up to 2 weapons.

### Formulas
#### Total Cost
(Initial Cost of 1) + RC + CC + T + HP + (sum of M) )

### Attributes
#### Ranged Combat (RC)
|Level        | 1    | 2    | 3    | 4    | 5   |
|:-:          |:-:   |:-:   |:-:   |:-:   |:-:  |
|Value        | 6+   | 5+   | 4+   | 3+   | 2+  |
|Modifier Cost|01.50 |02.50 |04.00 |06.50 |10.00|

Formula:
Point Cost = 1.585<sup>level</sup>

#### Close Combat (CC)
|Level        | 1    | 2    | 3    | 4    | 5   |
|:-:          |:-:   |:-:   |:-:   |:-:   |:-:  |
|Value        | 6+   | 5+   | 4+   | 3+   | 2+  |
|Modifier Cost|02.00 |04.00 |07.00 |13.00 |25.00|

Formula:
Point Cost = 1.903<sup>level</sup>

#### Toughness (T)
Minimum T is 2+

Formula:
Point Cost = ROUNDUP(1.2<sup>level</sup> + (Current Point Cost)

#### Hit Points (HP)
Minimum HP is 1<br>
Formula:
Point Cost = level<sup>2</sup>

#### Movement (M)
Formula: Point Cost = 1.1<sup>inches</sup> + (inches)

## Armor
### Combat Save (CS)
Highest value is a 2+

|Values     | 6+  | 5+  | 4+  | 3+  | 2+  |
|:-:        |:-:  |:-:  |:-:  |:-:  |:-:  |

## Weapons
|Attribute     | Dst | A   | S     | SM     | Point Cost |
|:-:           |:-:  |:-:  |:-:    |:-:     |:-:         |
|Initial Value | 0   | 1   | 1     | 1      | 3          |
|modifier Cost |00.25/6|04.00|01.50|Variable| -          |

### Distance (Dst)
Purchased in increments of 6"

After more than 12" have been added that weapon may no longer be used in Close Combat.

### Attacks (A)
Cannot be reduced to 0.

### Strength (S)
May be reduced to 0 for a return of 1 Point.

### Save Modifier (SM)
May be reduced to 0 for a return of 1 Point.

|Values     | -1  | -2  | -3  | -4  | -5  |
|:-:        |:-:  |:-:  |:-:  |:-:  |:-:  |
|Point Cost |01.00|02.50|06.25|16.00|40.00|         
|Formula| 01.00|01.00 * 02.50|02.50 * 02.50|06.25 * 02.50|16.00 * 02.50

## Special Abilities
### Unit

#### Deep Strike
* Cost: 02.00
* Stackable: No
* Description: When a unit has this ability, it is able to setup in reserve and attempt to enter play via deep strike.

#### Extra Weapon
* Cost: 04.00
* Stackable: Yes
* Description: Adds additional weapon to unit profile.

#### Inspirational
* Cost: 01.00
* Stackable: Yes
* Descrption: For each point taken, add +1 to the Morale roll.

#### Invincibility Save
* Cost: Chart
* Stackable: Yes
* Description: Adds the ability to take a save in a situation where no save would be permitted.

#### Mob Rule
* Cost: 01.00
* Stackable: No
* Description: Unit is now a rally point. When a unit with the status of fallback comes within 2" of this unit and that unit also has "Mob Rule" the units will merge status will be "Normal"

#### Rally to me
* Cost: 01.00
* Stackable: No
* Description: Unit is now a rally point, when a friendly unit with the status of fallback comes within 6" of this unit, friendly unit will regroup in morale phase and will change status to normal. 

#### Regeneration
* Cost: Chart

|Value         | 6+  | 5+  | 4+  | 3+  | 2+  |
|:-:           |:-:  |:-:  |:-:  |:-:  |:-:  |
|Modifier Cost |02.00|03.00|10.00|100.00|200.00|
* Stackable: Yes
* Description: When taken, unit is able to roll to regain lost HP at the start of turn during Morale phase. Roll a die for each HP lost. Upon successful roll, HP is regained. If unit is dead/destroyed, do not remove from game. Instead, perform this check first. 

#### Regroup
* Cost: 01.00
* Stackable: No
* Description: When unit has status of fallback, unit will automatically regroup in Morale Phase.


### Weapons
#### Burst Shot
* Cost: 00.25
* Stackable: No
* Descrption: When target is within 1/2 distance or less, double the number of attacks.
