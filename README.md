# Mini Python Problems

A collection of small beginner-friendly Python scripts, each solving a self-contained problem. Built for practicing core Python concepts like loops, conditionals, input handling, and string formatting.

## Projects

### 1. Basic Calculator (`basic_calculator`)
A simple command-line calculator that takes two numbers and an operator (`+`, `-`, `*`, `%`) and prints the result.

**Run:**
```bash
python basic_calculator
```

**Example:**
```
enter the sign value[+,-,*,%] : +
enter the 1st value: 5
enter the 1st value: 3
the sum of the number is: 8.0
```

---

### 2. Quiz Game (`quiz-game`)
A 5-question multiple-choice trivia quiz. Displays a question and four options (A–D), takes the user's guess, checks it against the correct answer, tracks the score, and prints a final percentage at the end.

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
enter your food items (q to quit): apple
enter the price of the:$apple 1.50
enter your food items (q to quit): q
=======your cart========
apple = 1.5
the total cost is :$1.5
```

---

### 4. Simple Interest Calculator (`simple_interest_calculator`)
Calculates compound interest based on principal, rate, and time, with input validation to ensure all values are greater than 0.

**Run:**
```bash
python simple_interest_calculator
```

**Example:**
```
enter the principle: 1000
enter the rate: 5
enter the time: 2
1102.5
```

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
- Scripts are saved without a `.py` extension in this repo. You may want to rename them (e.g. `basic_calculator.py`) for easier editing in most code editors.
- These are practice/learning scripts and are not hardened for production use (e.g. limited input validation in some cases).

## License
Feel free to use, modify, and learn from these scripts.
