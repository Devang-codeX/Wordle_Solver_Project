# 🎮 Wordle Solver (C++)

A command-line Wordle Solver built in C++ that helps users identify possible Wordle solutions using logical filtering techniques.

This project was inspired by coursework and further extended independently to strengthen problem-solving and algorithm design skills.

---

## ✨ Features

- 🔍 Dictionary-based word filtering
- 🎯 Position matching system
- 🔠 Letter inclusion & exclusion logic
- 💻 Interactive command-line interface
- 🔄 Reset and replay functionality

---

## ⚙️ How It Works

The solver narrows down possible words using:

1. Known letter positions  
2. Letters present but unknown position  
3. Letters not present in the word  

---

## 🛠 Technologies Used

- C++
- STL (`vector`, `string`, `algorithm`)
- File Handling
- Object-Oriented Programming

---

## ▶️ Compilation

```bash
g++ WordleSolver.cpp -o solver
```

---

## ▶️ Run

After compilation, run the program using:

```bash
./solver
```

---

## 📂 Project Files

| File | Description |
|------|-------------|
| `WordleSolver.cpp` | Main source code |
| `words.txt` | Word dictionary used for filtering |

---

## 🎯 Purpose

This project was created to practice:
- Algorithm design
- Logical filtering
- File handling
- Object-oriented programming in C++
