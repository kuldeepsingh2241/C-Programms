# ⭐ Name in Stars

A C program that uses nested loops to print my name as pixel-art style block letters made entirely of `*` characters — built while practicing loop control and pattern logic in C.

> Note: the pattern is hardcoded for this specific name, not a general text-to-stars generator.

## 📸 Output

<img width="631" height="168" alt="image" src="https://github.com/user-attachments/assets/f5446f5a-385d-453d-ad26-41492fa112e8" />


## 🛠 How it works

The program uses nested `for` loops to control row and column positions on the console, printing a `*` or a blank space at each position depending on whether that position falls on the "stroke" of a letter. Each letter of the name has its own loop logic hardcoded to draw its shape — the same core idea as classic star-pyramid pattern programs, just applied to letter shapes instead of triangles.

## ▶️ How to run

**Using GCC (Linux/macOS/Windows with MinGW):**
```bash
gcc "name.c" -o name
./name
```

**Using Code::Blocks:**
1. Open the `.c` file in Code::Blocks
2. Build and Run (`F9`)

## 📂 Files

| File | Description |
|------|-------------|
| `name.c` | Source code — prints the name pattern using loops |

## 🧠 What I learned

- Using nested loops to control 2D output on the console
- Mapping logical conditions to visual/character output
- Debugging spacing and alignment issues in console-based pattern printing

## 🚀 Possible improvements

- Generalize it so any letter can be generated dynamically from a character-to-pattern map, instead of each letter being hardcoded
- Let the user type in a name and have the program build the pattern for it
- Add color output using ANSI escape codes

---
*Built as part of learning C — loops and pattern printing.*
