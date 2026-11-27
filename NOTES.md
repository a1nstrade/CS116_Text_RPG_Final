# Development Notes

Personal notes for the **Text-Based RPG Dungeon Game** (CS-116, Fall 2026).

> This is a working notebook, not a record of completed features.

## Game Concept

**Theme / setting:**  
Going to revolve around Risk of Rain and is going to use ASCII art of RORR Sprites

**Player's goal:**  
Defeat A Teleporter Boss

**Win condition:**  
Beat The Boss

**Loss condition:**  
Die by The Boss

## Character Design

| Character type | Playable? | Unique attributes | Unique methods | Notes |
| Commando       | Yes       | Ammo              | shoot(), reload() ||
| Artificer      | Yes       | Energy            | castElemntalAttack(), recharge() | |
| Mercenary      | Yes       | Armor             | slash(), block() ||
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
