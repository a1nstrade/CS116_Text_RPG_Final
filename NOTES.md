# Development Notes

Personal notes for the **Text-Based RPG Dungeon Game** (CS-116, Fall 2026).

> This is a working notebook, not a record of completed features.

## Game Concept

**Theme / setting:**  
Going to revolve around Risk of Rain and is going to use ASCII art of RORR Sprites

**Player's goal:**  
Defeat Colossus

**Win condition:**  
Beat Colossus

**Loss condition:**  
Die by Colossus

## Character Design

| Character type | Playable? | Unique attributes | Unique methods | Notes |
| Commando       | Yes       | Ammo              | shoot(), meleeAttack() | He will recover ammo from dungeon events. Melee attacks do less damage when ammo runs out |
| Artificer      | Yes       | Energy            | castElementalAttack(), recharge() | Artificer will spend one tunr to recharge energy. Her elemental attacks deal a lot of damage but can run your energy out quick. She is the most vulnerable while recharging as she has low health |
| Mercenary      | Yes       | Armor             | slash(), block() | Armor reduces incoming damage and the durability can be recovered through a small chance of each dungeon room clear or repaired at HAN-D's shop. He can absorb multiple hits without losing much health, but the damage negation scales down after each time he is hit and eventually he is hit with the normal amount of damage the enemies deal |
| HAN-D         | No        | | | Shop NPC Where you pick between 3 items to buy that gets added to your inventory/action options |
| Lemurian       | No        | | | |
| Rock Golem     | No        | | | |
| Colossus       | No        | | | |

The assignment requires at least **five `Actor` subclasses**, including at least **three playable** character types.

## Class Design Notes

### `Actor`
- Required: `String name`
- Required: a health-point attribute
- Planned shared methods:
- Questions:

### `Event`
- Required: `String name`
- Required: `void happens(...)`
- Planned additional attributes:
- Planned event behavior:

### Application / Main Class
- Main entry point:
- Input / menu approach:
- Game-loop notes:

### Polymorphism
**Action shared by multiple character types:**  
_To decide._

**How character behaviors will differ:**  
_To decide._

## Dungeon & Event Ideas

| Room or event idea | Effect on player | Possible player choice |
|---|---|---|
| | | |
| | | |
| | | |

**Approach to random events:**  
_To decide._

## Java Concepts Learned

### Inheritance
- 

### Polymorphism
- 

### Randomness
- 

### File I/O (if used)
- 

## Problems & Solutions

| Date | Problem | What I tried | Solution / lesson |
|---|---|---|---|
| | | | |

## Questions to Revisit

- [ ] 

## Useful References

- Course assignment: `Project_2026F(1).pdf`
- 
