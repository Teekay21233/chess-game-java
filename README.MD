# Chess Game in Java (Terminal-Based)

A terminal-based chess game written in pure Java, built with object-oriented design principles. This project is currently under development and aims to fully implement standard chess rules with a clean and modular architecture.

## 📌 Features

- Turn-based gameplay
- Legal piece movement
- Piece capturing
- Check detection
- Clear terminal rendering of the board
- Modular OOP design (pieces, board, game logic, UI)

## 🚧 In Progress

- Checkmate detection
- Special rules (castling, en passant, pawn promotion)
- Game reset / restart
- Improved move validation and error handling

## 🎯 Objectives

- Practice Java and object-oriented programming
- Improve abstraction and system modeling skills
- Implement rule validation for a complex turn-based game
- Use clean code practices and single-responsibility principle

## 🛠 Technologies

- Java 17+
- CLI/Terminal-based interface
- No external libraries

## 📁 Project Structure

```
src/
├── application/         # Game entry point and main loop
├── board/               # Board, Position, and general movement logic
├── chess/               # Chess-specific rules and piece classes
```

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Teekay21233/chess-game-java.git
   cd chess-game-java
   ```

2. Compile the project:
   ```bash
   javac src/**/*.java
   ```

3. Run the main class:
   ```bash
   java src/application/Program
   ```

> You may also open the project in an IDE like IntelliJ IDEA or Eclipse and run `Program.java`.

## 💡 Next Steps

- Add unit tests
- Implement save/load game feature
- Create a simple AI opponent (optional)

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

Feel free to fork, suggest improvements, or contribute!
