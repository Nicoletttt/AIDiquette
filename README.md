# AIDiquette
### Learning Proper First Aid Procedures Through Scenario-Based Gameplay

A Java-based application that will teach basic first aid through an interactive, scenario-based game where players learn to choose the correct treatment for injured patients. Inspired by first aid training of Philippine Red Cross.

# Game Overview

- Genre: Educational Game, Simulation (Scenario-Based)
- Language: Java
- Course: OOP101 -Object Oriented Programming
- Section: CS-2103

## Features

- Scenario-based gameplay with 2D pixel-art visuals
- Three difficulty modes, each with its own emergency scenario
- A guide character who gives indirect hints
- Heart (life) system with a retry option
- Immediate feedback after every choice
- Multiple-choice buttons for simple, easy controls
- Certificate of completion after finishing a scenario
- Built with Object-Oriented Programming in Java


## OOP Concepts Used

| Concept       | Application |
|---------------|----------------------------|
| Classes and Objects  | Each part of the game, like the player, patient, scenario, and questions, is its own class |
| Methods              | Each class handles its own actions, like losing a heart, checking an answer, or giving a hint |
| Encapsulation        | Player and patient data are kept private, so they can only be changed in safe ways |
| Inheritance          | The three scenarios share the same basic setup from one parent scenario class, and all screens share one parent screen class |
| Polymorphism         | The game runs every scenario and screen the same way, but each one shows its own content |
| Abstraction          | The parent scenario and screen classes set what each one must have, while the details are left to each scenario or screen |
| Exception Handling   | Missing files or wrong inputes, like an empty name or invalid age, show a friendly message instead of crashing the game |
| Arrays/Data Handling | Store the scenarios, questions, answer choices, hints, and hearts |

## Project Limitations

- **Only three injury types:** Burned skin, open wound, and severed arm. Other emergencies are not covered.
- **One scenario per difficulty level:** Each mode has a single fixed case, so replaying it repeats the same steps.
- **Simplified first aid procedures:** The steps are basic and shortened for gameplay. They don't cover every real-life variation.
- **Not a replacement for formal training:** The game supports learning but does not certify anyone in first aid.
- **Multiple-choice only:** Players pick from buttons and cannot type commands, perform physical actions, or improvise.

## Team Members
norMe's - Team 10
| Name | Role | GitHub |
|------|------|--------|
| Victoria Nicole Liceralde | Coding, Game Testing, In-game Visual Design, Sprite Animation | Nicoletttt |
| Kurt Russell Jovero | Coding, Game Testing, In-game Visual Design, Visual Design Draft | KurtRussellJ |
| Aronne Josh Reña | Coding, Game Testing, In-game Dialogue, Audio Editing | IcedTeeth |

## Project Status

The project is currently **in development** for OOP 101 - Object-Oriented Programming course at Batangas State University, Alangilan Campus, for the First Semester of Academic Year 2026-2027. Features may be changed depending on the development of the game.
