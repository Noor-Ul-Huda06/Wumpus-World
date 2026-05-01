# Wumpus World: Logic Agent

A web-based implementation of the Wumpus World AI problem. This project demonstrates an autonomous agent that utilizes Propositional Logic to navigate a grid-based environment, avoid hazards, and successfully locate the gold.

## Project Access
- **Live Demo:** https://noor-ul-huda06.github.io/Wumpus-World/
- **GitHub Repository:** https://github.com/Noor-Ul-Huda06/Wumpus-World

## Technical Overview
The agent is designed using a Knowledge Base (KB) that processes environmental percepts (Breezes and Stenches). It applies inference to determine safe cells for navigation, ensuring a logical approach to decision-making under uncertainty.

## Key Features
- **Inference Engine:** Processes logical constraints to identify safe and dangerous tiles.
- **Autonomous Navigation:** The agent explores the grid based on proven safety, with built-in backtracking capabilities.
- **Configurable Environment:** Users can adjust grid size and pit density to test agent efficiency in varying conditions.
- **Real-time Log:** A Knowledge Base log displays the logical deductions made by the agent at every step.

## Methodology
The agent operates within the PEAS framework:
- **Performance:** Points awarded for finding gold, with penalties for movement and death.
- **Environment:** A grid containing random pits, a Wumpus, and one gold piece.
- **Actuators:** Moves and actions directed by logical inference.
- **Sensors:** Perception of Breeze (adjacent to pits) and Stench (adjacent to the Wumpus).

## Technology Stack
- **Languages:** JavaScript (ES6+), HTML5, CSS3
- **Design System:** Custom "Amethyst Noir" theme using CSS Grid and Flexbox.
- **Fonts:** Orbitron for headers and Exo 2 for body text.

---
Developed as a project for Artificial Intelligence studies.
