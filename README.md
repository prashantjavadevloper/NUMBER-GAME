# 🎮 Java Number Guessing Game

This is a simple and fun **console-based number guessing game** developed in Java. The program generates a random number between **1 and 100**, and the player has **5 chances** to guess it correctly in each round.

---

## ✅ Features

- ✅ Generates a **random number** between 1 and 100  
- 🎯 Player has **5 chances** to guess the number  
- 💡 Provides hints after each guess:
  - "User choiced number is larger"
  - "User choiced number is smaller"
- 🏆 Displays **congratulations** if the guess is correct  
- 🔄 Option to **play multiple rounds**  
- 📊 Displays **total score** (number of rounds won)  
- ❌ Handles **invalid menu choices**

---

## 📌 How It Works

1. Game starts with a menu:
   - `1 -> Want to play game`
   - `2 -> Exit`
2. If the player chooses to play:
   - A random number between 1 and 100 is generated.
   - Player has 5 attempts to guess the number.
   - After each guess, feedback is given:
     - If the guess is correct → round won, score increases.
     - If incorrect → hint whether the guess is higher/lower.
3. After 5 attempts (or a correct guess), the player is asked whether they want to play another round.
4. Game ends with a score summary.

---

## 🛠 Code Structure

- `getrandN(int min, int max)`:  
  Utility method that returns a random number between the provided `min` and `max`.

- `main(String[] args)`:  
  Handles:
  - Game menu
  - Random number generation
  - Guess checking logic
  - Score tracking
  - Replay option

---

## 🔧 Future Enhancements (Optional)

- 🏅 Assign scores based on the **number of attempts left**
- 📁 Save and load **high scores** using file handling
- 🧠 Add **difficulty levels** (e.g., Easy: 10 chances, Hard: 3 chances)
- 🖥️ Build a **GUI version** using Swing or JavaFX

---

## 💻 Requirements

- Java JDK 8 or above  
- Any Java IDE (Eclipse, IntelliJ, NetBeans) or text editor (VS Code)  
- Command Line / Terminal for execution

---

## 🚀 How to Run

1. Clone or download the repository
2. Open the `numbergame3.java` file in your Java IDE or text editor
3. Compile the code:
   ```bash
   javac numbergame3.java
