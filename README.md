# 🎮 Tic-Tac-Toe AI (Minimax Algorithm)

An **unbeatable Tic-Tac-Toe game** built in Java using the **Minimax algorithm**. Play against an AI that always makes the best possible move!

## 🚀 Features
✅ Play against an AI opponent  
✅ AI uses the **Minimax algorithm** for optimal moves  
✅ Ensures **win or draw**—never loses!  
✅ Command-line interface for easy play  

## 🧠 How Minimax Works
The **Minimax algorithm** evaluates all possible moves and selects the one that guarantees the best outcome for the AI:
1. **Scores each move**: +10 for AI win, -10 for AI loss, 0 for draw.  
2. **Simulates all possible game states**.  
3. **Chooses the move** that minimizes the worst-case scenario for AI.  

## 📜 Game Rules
- The game is played on a **3×3 grid**.  
- **Human ('X')** and **AI ('O')** take turns.  
- The first to get **three in a row** (horizontally, vertically, or diagonally) wins.  
- If all cells are filled and no one wins, it's a **draw**.  

## 🎮 How to Play
1. **Clone the repository**:
   ```sh
   git clone https://github.com/yourusername/TicTacToe-AI.git
   cd TicTacToe-AI

2.Compile & Run the Java program:
   javac TicTacToe.java
   java TicTacToe
