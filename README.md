# Wordle Solver (C++)

A command-line Wordle Solver implemented in C++ that helps users
identify possible Wordle solutions using logical filtering techniques.

This project was inspired by coursework and further extended independently to demonstrate algorithm design and problem-solving skills.

## Features
- Dictionary-based word filtering
- Position matching system
- Letter inclusion and exclusion logic
- Interactive command-line interface
- Reset and replay functionality

## How It Works
The solver reduces possible words by applying:
1. Known letter positions
2. Letters present but unknown position
3. Letters not present in the word

## Technologies Used
- C++
- STL (vector, string, algorithm)
- File Handling
- Object-Oriented Programming

## Compilation

```bash
g++ WordleSolver.cpp -o solver
.\solver

## Run

After compilation, run the program using:

```bash
solver
