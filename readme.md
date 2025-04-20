# 🎰 Python Slot Machine Game
 
A simple **command-line slot machine game** built with Python! This project is beginner-friendly and demonstrates basic concepts like functions, loops, user input, randomness, and game logic.

---

## ✨ Features

- Simulates a 3x3 slot machine 🎰  
- Customizable number of lines to bet on (1–3)
- Adjustable bet per line with min/max limits
- Calculates winnings based on symbol values and matching lines
- Includes input validation and balance management

---

## 📸 Gameplay Preview

```
What Would like to deposit? $100
Enter The Numbers Of Lines To Bet On (1-3)? 2
What Would like to bet on each line? $10
You're Betting $10 on 2 lines. Total Bet is equal to: $20
A | C | D
B | A | B
C | D | C
you won $10
you won on lines: 2
```

---

## 🛠️ How to Run

1. **Clone the repository**  
```bash
git clone https://github.com/yourusername/slot-machine-game.git
cd slot-machine-game
```

2. **Run the game**  
Make sure Python is installed (version 3+), then run:

```bash
python slot_machine.py
```

---

## 🔧 Game Rules & Logic

- Each spin generates a 3x3 grid of random symbols: **A, B, C, D**
- Each symbol has a value:
  - A: $5
  - B: $4
  - C: $3
  - D: $2
- Winnings are calculated per line when **all symbols in a line match**
- You can bet on up to 3 lines, and your total bet is `bet amount × number of lines`

---

## 📁 File Structure

```
slot-machine-game/
│
├── slot_machine.py      # Main game logic
├── README.md            # Project documentation
```

---

## 🚀 Future Ideas

- Add diagonal win detection  
- Add color or emojis to symbols for a more visual CLI
- Create a GUI version with Tkinter or Pygame  
- Track stats (total games played, win/loss ratio)

---

## 👨‍💻 Author

**Nawaf Rayhan**  
[GitHub](https://github.com/nawaf-rayhan585)

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).
