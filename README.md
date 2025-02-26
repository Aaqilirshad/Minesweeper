# Minesweeper AI with Pygame Interface

This project implements the classic Minesweeper game with an AI agent that plays the game using inferences and propositional logic. The game features a graphical interface built with Pygame, allowing users to visualize the AI's decision-making process in real-time.

## Features

- **Graphical Interface**: Utilizes Pygame to render the Minesweeper board, providing a clear visualization of the game state.
- **AI Agent**: Employs propositional logic to deduce safe moves and identify mines, enhancing its performance over time.
- **Real-Time Updates**: Observe the AI as it marks cells, makes moves, and updates its knowledge base dynamically.


## How It Works

The AI operates by constructing a knowledge base of logical sentences that represent the state of the board. Each sentence consists of a set of cells and a count of how many of those cells contain mines. By iteratively updating this knowledge base and making inferences, the AI deduces safe moves and identifies mines.

The core components include:

- **Minesweeper Class**: Represents the game board and handles mine placement and neighbor calculations.
- **Sentence Class**: Encapsulates logical statements about the board, aiding the AI in making inferences.
- **MinesweeperAI Class**: Implements the logic for updating the knowledge base, marking cells as safe or as mines, and selecting the next move.
