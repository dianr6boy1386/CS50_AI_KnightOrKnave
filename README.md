# CS50 AI 'Knights and Knaves'
## by Dyan Ahmadi 

A solution to the Knights and Knaves problem set from Harvard's CS50's Introduction to Artificial Intelligence with Python.

## Overview

This project uses propositional logic to solve a series of Knights and Knaves puzzles.

In these puzzles:

- Knights always tell the truth.
- Knaves always lie.
- Each character is either a knight or a knave.


The project represents these facts with logical symbols and uses the provided `model_check` function to determine which statements are logically entailed by the knowledge base.

## Project Structure

```text
.
├── puzzle.py
├── logic.py
└── README.md
```

## Puzzles

### Puzzle 0

A says:

> "I am both a knight and a knave."

### Puzzle 1

A says:

> "We are both knaves."

B says nothing.

### Puzzle 2

A says:

> "We are the same kind."

B says:

> "We are of different kinds."

### Puzzle 3

A says either:

> "I am a knight."

or:

> "I am a knave."


B says:

> "A said 'I am a knave'."

B also says:

> "C is a knave."

C says:

> "A is a knight."



## Concepts Used

### Propositional Logic

Each statement is represented as a proposition that can be either true or false.

For example:

```python
AKnight = Symbol("A is a Knight")
AKnave = Symbol("A is a Knave")
```

### Logical Operators

The project uses logical operators provided by `logic.py`, including:

- `And`
- `Or`
- `Not`
- `Implication`

These operators allow the English statements from each puzzle to be translated into formal logical expressions.



## How to Run

Make sure Python is installed on your system.

From the project directory, run:

```bash
python puzzle.py
```

The program prints the conclusions for each puzzle.


## What I Learned

This project demonstrates how natural language statements can be converted into formal logic and solved through model checking.

The main skills practiced are:

- Propositional logic
- Logical implication
- Knowledge representation
- Model checking
- Translating natural language into formal expressions
- Reasoning about mutually exclusive possibilities

## Course

Harvard University CS50's Introduction to Artificial Intelligence with Python.

Project: Knights and Knaves
