# Project TODO & Development Phases

**Course:** CS-116 — Fall 2026  
**Due:** December 6, 2026  
**Goal:** Build a playable text-based Java RPG dungeon game.

Check off tasks only after they are working. The phases are a suggested workflow; the requirements are based on the assignment.

## Phase 1 — Planning & Design

**Objective:** Decide how the game works and how its classes fit together.

- [ ] Choose the dungeon theme and overall game concept.
- [ ] Define the win condition.
- [ ] Define the loss condition.
- [ ] Plan at least three playable character types.
- [ ] Plan at least five total `Actor` subclasses.
- [ ] Plan dungeon room choices and event types.
- [ ] Sketch a class diagram.

**Done when:** The main game rules and class relationships are clear.

## Phase 2 — Character System

**Objective:** Build and test the character hierarchy.

- [ ] Create an `Actor` superclass.
- [ ] Add `String name`.
- [ ] Add a health-point attribute.
- [ ] Add shared character methods as needed.
- [ ] Create at least five subclasses of `Actor`.
- [ ] Make at least three subclasses selectable by the player.
- [ ] Give some subclasses unique attributes.
- [ ] Give some subclasses unique methods.
- [ ] Demonstrate polymorphism: different characters respond differently to the same action.
- [ ] Test character behaviors.

**Done when:** Character classes compile and demonstrate inheritance and polymorphism.

## Phase 3 — Event System

**Objective:** Make dungeon events work.

- [ ] Create the `Event` class.
- [ ] Add `String name`.
- [ ] Implement `void happens(...)`.
- [ ] Make events affect the player character.
- [ ] Implement random or pseudo-random event selection.
- [ ] Verify that playthroughs encounter mostly different events.
- [ ] Show event descriptions and their effects clearly.

**Done when:** Events can occur and update game state.

## Phase 4 — Dungeon & Core Gameplay

**Objective:** Connect character choice, rooms, events, and game endings.

- [ ] Create an application class with `main()`.
- [ ] Guide the player through character selection.
- [ ] Offer multiple dungeon rooms to choose from.
- [ ] Allow room selection throughout gameplay.
- [ ] Trigger a room event after entering.
- [ ] Allow responses to events when needed.
- [ ] Continue until the player dies or finishes the dungeon.
- [ ] Implement win and loss conditions.

**Done when:** A full game can be played from start to finish.

## Phase 5 — Game Flow & User Experience

**Objective:** Make the console game easy to understand and replay.

- [ ] Explain the available choices at each step.
- [ ] Display changes to the player's state after events.
- [ ] Handle invalid player choices.
- [ ] Display a clear win or loss result.
- [ ] Let the player restart or exit.
- [ ] Test multiple playthroughs.

**Done when:** The complete gameplay loop is understandable and reliable.

## Phase 6 — Optional Extra Credit (+20 Points)

**Objective:** Implement **at least one** optional feature if pursuing extra credit.

- [ ] Choose an optional feature:
  - [ ] Multiplayer: control a team of main characters, with events interacting with all members.
  - [ ] NPCs: design and use at least three NPC types as `Actor` subclasses; events contain NPCs.
  - [ ] File-based events: store at least 50 different event objects' details in a file and load them at startup.
  - [ ] Save/load: save progress, exit, and later resume the game.
- [ ] Implement and test the chosen feature.
- [ ] Record the implemented feature in the README.

**Done when:** At least one optional feature meets the assignment description.

## Phase 7 — Testing, Documentation & Submission

**Objective:** Prepare all required deliverables.

- [ ] Test a winning playthrough.
- [ ] Test a losing playthrough.
- [ ] Test restarting and exiting.
- [ ] Verify random or pseudo-random events.
- [ ] Verify the required classes and polymorphism.
- [ ] Finalize the class diagram. **(20 points)**
- [ ] ZIP the complete Java project. **(70 points + potential 20 extra)**
- [ ] Complete `README.md` with:
  - [ ] How to start the game.
  - [ ] Which optional features were implemented.
  - [ ] How polymorphism is implemented.
- [ ] Submit all three deliverables on Canvas. **(README: 10 points)**

**Done when:** The class diagram, Java ZIP, and README are ready to submit.

---

## Assignment Reminders

- Maximum team size: **3 students**.
- One team member fills out the team information form.
- One Canvas submission per team.
- Base project: **100 points**, plus **20 possible extra-credit points**.

## Current Focus

**Phase:**  
**Next task:**  
**Blocker / question:**  
