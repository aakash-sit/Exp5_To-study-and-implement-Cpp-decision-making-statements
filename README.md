Aakash Choudhari

E&TC-A2

24070123031

# 🧠 Experiment 5 – Decision Making Statements in C++

## 🎯 Aim
To study and implement **decision making statements** in C++ such as:
- `if` statement
- `if-else` statement
- `else-if` ladder
- `switch` statement

---

## 📘 Theory

Decision making in C++ allows the program to choose between different paths of execution based on conditions.

---

### 🔹 1. `if` Statement
Used to execute a block of code if a specified condition is true.

**Syntax:**
```cpp
if (condition) {
    // code executes if condition is true
}
```

---

### 🔹 2. `if-else` Statement
Executes one block if the condition is true, another block if false.

**Syntax:**
```cpp
if (condition) {
    // code if condition is true
} else {
    // code if condition is false
}
```

---

### 🔹 3. `else-if` Ladder
Allows testing of multiple conditions sequentially.

**Syntax:**
```cpp
if (condition1) {
    // block1
} else if (condition2) {
    // block2
} else {
    // default block
}
```

---

### 🔹 4. `switch` Statement
Used when a variable is compared against a list of constant values.

**Syntax:**
```cpp
switch (expression) {
    case value1:
        // code
        break;
    case value2:
        // code
        break;
    default:
        // default code
}
```

---

## ⚙️ Procedure

1. Start a C++ program using `#include <iostream>` and `using namespace std;`.
2. Define required variables and take input (e.g., a number, character, etc.).
3. Apply each of the following structures:
   - `if`
   - `if-else`
   - `else-if`
   - `switch`
4. Compile and execute the code to observe decision-making flow.
5. Modify conditions to test different outcomes.

---

## 🧪 Example Use-Cases

- Check if a number is positive or negative (`if-else`)
- Grade evaluation using `else-if` ladder
- Menu-driven calculator using `switch`

---

## 📌 Key Concepts Covered

- Conditional branching
- Comparison and logical operators (`==`, `!=`, `>`, `<`, `&&`, `||`)
- Importance of `break` in `switch` statements
- Difference between `if-else` ladder and `switch`

---

## 🎓 Learning Outcomes

- Understood how to control program flow using conditions.
- Practiced applying decision making logic in real-world tasks.
- Gained clarity on when to use `if`, `if-else`, `else-if`, and `switch`.
- Learned how to prevent fall-through in `switch` using `break`.

---

## 📝 Experiment Summary

This experiment focused on C++ **decision making statements**, which allow a program to choose between multiple paths of execution. These control structures form the basis of logic implementation and are essential for building intelligent, responsive applications.

---
