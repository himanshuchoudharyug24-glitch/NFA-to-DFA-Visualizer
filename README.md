# 🚀 NFA to DFA Visualizer

<p align="center">
  A simple and interactive project to understand how NFA is converted into DFA
</p>

---

## 📌 About this project

This project is a web-based tool that converts a **Non-Deterministic Finite Automaton (NFA)** into a **Deterministic Finite Automaton (DFA)**.

The goal of this project is to understand the concept of **subset construction** in a practical way. Instead of only learning theory, this tool helps visualize how the conversion actually happens.

---

## 👨‍🎓 Student Details

* **Name:** Himanshu Choudhary
* **Roll Number:** 2024UCS1604

---

## ✨ Features

* 🔄 Convert NFA to DFA
* 📊 Visual representation using graphs
* 📋 Transition tables for both NFA and DFA
* 🌙 Dark mode option
* 🎨 Color theme toggle
* 🧠 Basic explanation of output

---

## ⚙️ How it works

The conversion is done using the **subset construction method**.

* Each DFA state represents a **set of NFA states**
* A queue is used to explore all possible states
* The process continues until no new states are generated

---

## ▶️ How to run

1. Download or clone the repository
2. Open `index.html` in your browser
3. Enter your NFA details
4. Click **Convert**

---

## 🧪 Example input

```json
{
"q0":{"0":["q0","q1"],"1":["q0"]},
"q1":{"1":["q2"]},
"q2":{}
}
```

---

## 📈 Output

After clicking convert, the project will show:

* NFA Graph
* DFA Graph
* NFA Transition Table
* DFA Transition Table
* Explanation

---

## 📚 What I learned

* Practical understanding of NFA and DFA
* Implementation of subset construction
* Using JavaScript for logic building
* Graph visualization using vis.js

---

## 🔮 Future improvements

* Step-by-step animation
* Export results
* Improved UI design

---

## 📝 Note

This project is created as part of academic learning and is mainly focused on understanding concepts.

---

## ⭐ Final Thought

Building this project helped me understand automata theory in a much clearer and practical way.


