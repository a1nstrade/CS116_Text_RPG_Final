# Text-Based RPG Dungeon Game

## Project Overview

This project is a text-based Role-Playing Game (RPG) developed in Java for **CS-116 (Fall 2026)**.

The player selects a character and explores a dungeon by choosing which rooms to enter. Each room contains a random event that may affect the player's health, abilities, or collected rewards.

The objective is to survive the dungeon and meet the conditions necessary to win the game.

The project focuses on applying **Object-Oriented Programming (OOP)** concepts, including inheritance, polymorphism, classes, objects, attributes, and methods.

## Game Description

The game follows a dungeon exploration system where the player makes decisions that influence their progress.

### Gameplay

1. **Character Selection:** The player chooses a main character from at least three available character types.
2. **Dungeon Exploration:** The player selects which dungeon room to enter next.
3. **Random Events:** Each room contains a randomly selected event, such as an enemy attack, healing encounter, or reward.
4. **Character Progression:** Events may affect the character's health, power, or collected rewards.
5. **Winning and Losing:** The player continues exploring until their character dies or successfully completes the dungeon.
6. **Replayability:** After the game ends, the player can choose to restart or exit.

## Project Requirements

### 1. Java Classes

The project must contain the following classes:

- **Actor:** A superclass representing characters in the game.
- **At least five Actor subclasses:** Different character types, including at least three playable character types.
- **Event:** A class representing events that occur inside dungeon rooms.
- **Application class:** Contains the `main()` method used to start the game.

Additional classes may be created as needed.

### 2. Actor Class

The `Actor` superclass must contain:

- A `String name` attribute.
- An attribute representing health points.
- Methods that define character behavior.

Some subclasses must introduce unique attributes and methods that are not present in the superclass.

### 3. Event Class

The `Event` class must contain:

- A `String name` attribute.
- A `void happens(...)` method that executes an event.

Events can affect the player through combat, healing, rewards, or other interactions.

### 4. Object-Oriented Programming

The project must demonstrate:

- **Inheritance:** Different character types extend the `Actor` superclass.
- **Polymorphism:** Different character types respond differently to the same actions or events.
- **Encapsulation and class organization:** Organizing character data and behavior into Java classes.

### 5. Game Functionality

The game must:

- Allow the player to select a character.
- Provide multiple dungeon room choices.
- Generate random or pseudo-random events.
- Explain events and their effects on the player.
- Allow player interaction throughout gameplay.
- Track the player's progress and health.
- Determine whether the player wins or loses.
- Display the final results.
- Allow the player to restart or exit.

## Optional Features (Extra Credit)

The assignment offers an additional **20 points** for implementing at least one of the following features.

### Multiplayer Mode
Allow the player to control multiple characters as a team, with events affecting every team member.

### Non-Player Characters (NPCs)
Implement at least three NPC types as subclasses of `Actor`, allowing them to interact with the player's character during events.

### File-Based Events
Store information about at least 50 different events in a file and load them into the game when it starts.

### Save and Load
Allow the player to save their progress, exit the game, and continue from their saved state later.

## Technologies

- **Programming Language:** Java
- **Development Environment:** Eclipse IDE
- **Java Version:** Java 21
- **Interface:** Text-based console application

## How to Run the Game

*Instructions will be added as development progresses.*

## Polymorphism Implementation

*An explanation of how polymorphism is implemented will be added after the character classes and their behaviors are developed.*

## Implemented Optional Features

*This section will be updated if any extra-credit features are implemented.*

## Assignment Information

- **Course:** CS-116
- **Semester:** Fall 2026
- **Project Type:** Team Project
- **Maximum Team Size:** 3 students
- **Due Date:** December 6, 2026
- **Base Points:** 100
- **Extra Credit:** 20
- **Maximum Possible Points:** 120

### Required Deliverables

1. UML class diagram illustrating the program's design.
2. Complete Java project submitted as a ZIP file.
3. README documentation explaining how to run the game, implemented optional features, and the use of polymorphism.

---

**Project Status:** In Development

- NOTE: Minimal amount of AI will be used. Only use of AI so far: Created the README based on project PDF, Created the .md files for bases