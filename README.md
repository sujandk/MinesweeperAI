# MinesweeperAI

A Python-based Minesweeper game with an AI player that uses logical inference to identify safe moves and avoid mines. The AI leverages a knowledge-based system to strategically reveal cells on the board while keeping track of known safe cells and mines.

<h3>Overview</h3>
This project implements the classic Minesweeper game in Python with an AI component. The AI player autonomously analyzes the board and makes moves based on logical deductions. Using set-based logic, it infers the presence of mines in specific cells, thereby improving its success rate in identifying safe moves over random guessing.

The project serves as an excellent demonstration of basic AI concepts, such as logical reasoning, rule-based knowledge representation, and game automation.

<h3>Setup and Installation</h3>
Prerequisites: Make sure you have Python 3.x installed.
Clone the repository: git clone https://github.com/sujandk/minesweeperai.git
                      cd minesweeper-ai

<h3>AI Inference Engine</h3>
The AI uses the following functions to make decisions:

known_mines and known_safes: These functions identify if certain cells are definitively mines or safe based on existing knowledge.

mark_mine and mark_safe: These functions update the AI's knowledge base by marking cells as either mines or safe cells.

add_knowledge: The core logic that:
  Marks a cell as a safe move.
  Adds new sentences to the knowledge base based on neighbor cells.
  Deducts safe and mine cells through logical inference.
  The AI prioritizes safe moves but will make a random move if no safe moves are deducible.

![Screenshot 2024-10-25 at 11 57 20 AM](https://github.com/user-attachments/assets/eb0bfa8a-0513-4cae-839e-724f5634a76f)

![Screenshot 2024-10-25 at 11 57 35 AM](https://github.com/user-attachments/assets/90e0a9a6-f71a-4967-a568-5366448b0286)





