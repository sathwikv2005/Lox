# Lox Programming Language Interpreter

This repository contains my **from-scratch implementation of the Lox programming language**, developed by closely following _Crafting Interpreters_ and extending it with my own language features and design decisions.

---

## Features

- **Recursive descent parser** with a hand-written scanner
- **Abstract Syntax Tree (AST)** generation and evaluation
- **Lexical scoping** with static resolution
- **First-class functions & closures**
- **Classes and instances**
- **Inheritance and dynamic method dispatch**

---

## ▶️ Running the Interpreter

```bash
javac *.java
java Lox
```

Run a Lox file:

```bash
java Lox path/to/file.lox
```

---

## 📌 Example

```lox
class Counter {
  Counter(start) {
    this.value = start;
  }

  inc() {
    this.value = this.value + 1;
  }
}

var c = Counter(0);
c.inc();
print c.value; // 1
```

---

## 📖 Reference

- _Crafting Interpreters_ — Robert Nystrom

---

## 🔮 What’s Next

- Add this project to my **portfolio & resume**
- Build **Helium**, a custom programming language and bytecode VM in C
- Implement a **Game Boy emulator** to deepen low-level systems knowledge

---

## 📜 License

This project is for educational purposes. All language design credit for Lox goes to Robert Nystrom.
