# Unit Creation
How to build an unit for a squad.

## Base Unit
|Attribute    | RC  | CC  | T   | HP  | CS  | M   | Point Cost |
|:-:          |:-:  |:-:  |:-:  |:-:  |:-:  |:-:  | :-:        |
|Initial Value| 0   | 0   | 2+  | 1   | 0   | 0   | 1          |
|Modifier Cost|00.25|00.50|01.00|03.00|01.00|00.25| -          |

Unit is armed with up to 2 weapons.

Base Multiplier:
|Base Cost    | 0 - 10 | 11 - 15 | 16+ |
|:-:          |:-:     |:-:      |:-:  |
|Value        | 1      | 1.5     | (cost * 0.1) |

### Formulas
#### Total Cost
[ (Initial Cost = 1) + ( (sum of RC) + (sum of CC) + (sum of T) + (sum of HP) + (sum of CS) + (sum of M) ) ] * (Base Multipler)

### Attributes
#### Ranged Combat (RC)
|Values     | 6+  | 5+  | 4+  | 3+  | 2+  |
|:-:        |:-:  |:-:  |:-:  |:-:  |:-:  |

#### Close Combat (CC)
|Values     | 6+  | 5+  | 4+  | 3+  | 2+  |
|:-:        |:-:  |:-:  |:-:  |:-:  |:-:  |

#### Toughness (T)
Minimum T is 2+

#### Hit Points (HP)
Minimum HP is 1

#### Combat Save (CS)
Highest value is a 2+
|Values     | 6+  | 5+  | 4+  | 3+  | 2+  |
|:-:        |:-:  |:-:  |:-:  |:-:  |:-:  |

#### Movement (M)
00.25 for each additional inch.

## Weapons
|Attribute     | Dst | A   | S   | SM  | Point Cost |
|:-:           |:-:  |:-:  |:-:  |:-:  |:-:         |
|Initial Value | 0   | 1   | 1   | 1   | 3          |
|modifier Cost |00.25/6|01.25|01.50|Var| -          |

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

## Special Abilities
### Unit
#### Inspirational
* Cost: 01.00
* Stackable: Yes
* Descrption: For each point taken, add +1 to the Morale roll.

#### Regeneration
* Cost: See chart

|Value         | 6+  | 5+  | 4+  | 3+  | 2+  |
|:-:           |:-:  |:-:  |:-:  |:-:  |:-:  |
|Modifier Cost |02.00|03.00|05.00|10.00|20.00|
* Stackable: Yes
* Description: When taken, unit is able to roll to regain lost HP at the start of turn during Morale phase. Roll a die for each HP lost. Upon successful roll, HP is regained. If unit is dead/destroyed, do not remove from game. Instead, perform this check first. 

#### Regroup
* Cost: 01.00
* Stackable: No
* Description: When unit has status of fallback, unit will automatically regroup in Morale Phase.

#### Deep Strike
* Cost: 02.00
* Stackable: No
* Description: When a unit has this ability, it is able to setup in reserve and attempt to enter play via deep strike.

#### Mob Rule
* Cost: 01.00
* Stackable: No
* Description: Unit is now a rally point. Additionally, when a unit with the status of fallback comes within 2" of this unit and that unit also has "Mob Rule" the units will merge status will be "Normal"

#### Rally to me
* Cost: 01.00
* Stackable: No
* Description: Unit is now a rally point and when a friendly unit with the status of fallback comes within 6" of this unit, friendly unit will regroup in morale phase and will change status to normal.

### Weapons
#### Burst Shot
* Cost: 00.25
* Stackable: No
* Descrption: When target is within 1/2 distance or less, double the number of attacks.
