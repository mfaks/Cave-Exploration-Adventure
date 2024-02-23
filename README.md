# Cave-Exploration-Adenture - Text-Based Adventure Game in C++

## Introduction
Cave Exploration Adventure is a text-based adventure game set inside the cave of the Wumpus, a scary, gold-hoarding monster who likes to eat people who disturb its sleep. The player's goal is to guide an adventurer to kill the Wumpus, find its hidden gold, and escape alive. This game aims to replicate the classic Cave Exploration Adventure gameplay experience in C++.

## Description
Cave Exploration Adventure is a game where the player navigates through a cave filled with hazards and treasures, including bottomless pits, super bats, and gold. The player's actions include moving through tunnels to adjacent rooms, firing arrows to kill the Wumpus, and avoiding hazards. The game provides percept messages to inform the player about nearby events, such as the smell of the Wumpus, the flapping of bat wings, the feeling of a breeze from a pit, or the sight of glimmering gold.

## Key Components
- **The Adventurer:** Represents the player character, capable of moving through tunnels and firing arrows.
- **The Wumpus:** The main antagonist, residing in the cave and awakening when disturbed by the adventurer or an arrow.
- **Hazards:** Includes bottomless pits and super bats, posing threats to the adventurer's safety.
- **Gold:** Hidden treasures scattered throughout the cave, which the adventurer must find and collect.
- **Percepts:** Messages indicating the proximity of hazards or treasures to the adventurer's current location.

## Object-Oriented Programming Elements Used
- **Abstraction:** Implemented a flexible grid-based cave system with vectors for room navigation.
- **Polymorphism:** Utilized polymorphism to handle interactions between the user and game objects.
- **Encapsulation:** Encapsulated the functionality of game objects such as the adventurer, hazards, and gold, ensuring that each object's behavior was encapsulated within their respective classes.
- **Inheritance:** Utilized inheritance to create a hierarchy of game events, with common behaviors and properties defined in a base class and specialized behaviors implemented in derived classes.

## Compilation Instructions
To compile the Cave Exploration Adventure game, follow these steps:
1. Open a terminal.
2. Navigate to the directory containing the source code files.
3. Use following commond to enable the Makefile to compile the code:  
    `Make`
4. Upon successful compilation, an executable file named `explore` will be created in the same directory.
5. Run the game by executing the command:     
    `./explore`
