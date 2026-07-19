# Mini Python Problems

A collection of small beginner-friendly Python scripts, each solving a self-contained problem. Built for practicing core Python concepts like loops, conditionals, input handling, randomness, and string formatting.

## Projects

### 1. Basic Calculator (`basic_calculator`)
A simple command-line calculator that takes two numbers and an operator (`+`, `-`, `*`, `%`) and prints the result.

**Run:**
```bash
python basic_calculator
```

---

### 2. Quiz Game (`quiz-game`)
A 5-question multiple-choice trivia quiz. Displays a question and four options (A-D), takes the user's guess, checks it against the correct answer, tracks the score, and prints a final percentage at the end.

**Run:**
```bash
python quiz-game
```

**Features:**
- Loops through a set of general-knowledge questions
- Validates each guess against the correct answer
- Displays a recap of correct answers vs. user guesses
- Calculates and prints a final score as a percentage

---

### 3. Shopping Cart (`shopping-cart`)
An interactive shopping cart builder. Keeps prompting for food items and their prices until the user types `q` to quit, then prints the cart contents and total cost.

**Run:**
```bash
python shopping-cart
```

**Example:**
```
enter your food items (q to quit):apple
enter the price of the:$apple 1.50
enter your food items (q to quit):q
=======your cart========
apple = 1.5
the total cost is :$1.5
```

**Known issue:** the final loop that prints each cart item always displays the *last* price entered (`price` is left over from the prior loop) instead of each item's own price - worth fixing if you revisit this one.

---

### 4. Simple Interest Calculator (`simple_interest_calculator`)
Calculates compound interest based on principal, rate, and time, with input validation to ensure all values are greater than 0.

**Run:**
```bash
python simple_interest_calculator
```

---

### 5. Number Guessing Game (`guess-number`)
A "guess the number" game where the computer picks a random number and tells you if your guess is too high or too low, tracking how many guesses it takes.

**Run:**
```bash
python guess-number
```

**Note:** this file currently contains two separate versions of the game back to back (a "basic" version and a more advanced version with input validation), separated by stray text. As-is, running the file will error out partway through since the leftover labels aren't valid Python - split these into two files (e.g. `guess-number-basic`, `guess-number-advanced`) or clean up the extra text to make it runnable.

---

### 6. Rock, Paper, Scissors (`rock-paper-scissors`)
A classic rock-paper-scissors game against the computer. Keeps playing rounds, tracks your score, and asks after each round if you want to keep playing.

**Run:**
```bash
python rock-paper-scissors
```

**Features:**
- Validates that your input is one of `rock`, `paper`, or `scissors` before proceeding
- Tracks and prints your win count across rounds
- Lets you keep playing multiple rounds via a `y`/`n` prompt

---

### 7. Countdown Timer (`Count-down`)
A countdown timer that takes a number of seconds and counts down to zero, printing the remaining time in `HH:MM:SS` format.

**Run:**
```bash
python Count-down
```

**Known issue:** this file currently has inconsistent indentation (mixing tabs/spaces oddly), which will raise an `IndentationError` as-is. It needs the body of the loop re-indented consistently before it will run.

## Requirements
- Python 3.x
- No external libraries required

## Getting Started

Clone the repo and run any script directly with Python:

```bash
git clone https://github.com/kalyan405111/mini-python-problem.git
cd mini-python-problem
python <script-name>
```

## Notes
- Scripts are saved without a `.py` extension in this repo. Renaming them (e.g. `basic_calculator.py`) makes them easier to open and edit in most code editors.
- These are practice/learning scripts, not production code - a few (noted above) have small bugs or leftover debug text worth cleaning up.

## License
Feel free to use, modify, and learn from these scripts.
