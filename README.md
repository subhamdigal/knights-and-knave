# Knights and Knaves Logic Puzzle Solver

This project implements a logical reasoning engine to solve classic "Knights and Knaves" puzzles using propositional logic and model checking.

## 🧠 About

In these puzzles:
- **Knights** always tell the truth.
- **Knaves** always lie.

The goal is to determine who's who based on their statements.

The logic is implemented using custom classes (`Symbol`, `And`, `Or`, `Not`, etc.) and evaluated with a recursive model-checking algorithm.

## 📁 Files

- `logic.py` - Core logic representation (propositional formulas and model checking).
- `puzzle.py` - Definitions for four Knights and Knaves puzzles and their solutions.

## 🚀 How to Run

```bash
python puzzle.py
