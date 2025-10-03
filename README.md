# Cpp_Exp_15_recursion

# 🚀 Experiment-15: Recursion in C++

## 📌 AIM
To study and implement recursion in C++ through four different programs:
1. Factorial of a number  
2. Reverse digits of a number  
3. Reverse a string  
4. Sum of natural numbers  

---

## 🎯 OBJECTIVES
- To understand the principle of recursion and its working mechanism.  
- To learn how problems can be broken down into smaller subproblems.  
- To differentiate recursion from iteration.  

---

## 📖 THEORY

### 🔹 What is Recursion?
Recursion is a programming technique in which a function solves a problem by calling itself.  
It continues until a **base case** is reached.  

- **Base Case (Termination Condition):** Prevents infinite recursion.  
- **Recursive Case:** Defines how the problem reduces into smaller subproblems.  

### 🔹 Working of Recursion
- Each recursive call is stored on the **function call stack**.  
- Once the base case is reached, calls start resolving in **reverse order** (stack unwinding).  

### 🔹 Types of Recursion
- Direct Recursion  
- Indirect Recursion  
- Tail Recursion  
- Head Recursion  

### ✅ Advantages
- Elegant and simple solutions  
- Matches mathematical definitions  
- Useful for factorial, Fibonacci, string reversal, tree traversal  

### ⚠️ Disadvantages
- More memory usage (stack)  
- Slower than iteration  
- Risk of **stack overflow** if base case is missing  

---

## 📊 COMPARISON TABLE

| Program          | Base Case Condition   | Recursive Formula                  | Example Input | Example Output | Concept Focus            |
|------------------|----------------------|------------------------------------|---------------|----------------|--------------------------|
| Factorial        | n ≤ 1 → 1            | n × factorial(n-1)                 | 5             | 120            | Multiplication recursion |
| Reverse Digits   | n = 0 → stop         | print(n % 10), reverse(n/10)       | 123           | 321            | Number reversal          |
| Reverse String   | End of string → stop | reverse(str+1), print(str)         | HELLO         | OLLEH          | String reversal          |
| Sum of Numbers   | n ≤ 1 → 1            | n + sum(n-1)                       | 5             | 15             | Addition recursion       |

---

## 🧮 ALGORITHMS

### 1. Factorial of a Number
- Input n  
- If n ≤ 1 → return 1  
- Else → return n × factorial(n-1)  

### 2. Reverse Digits of a Number
- Input n  
- If n == 0 → return  
- Else → print n % 10, call reverse(n/10)  

### 3. Reverse a String
- Input string  
- If end reached → return  
- Else → call reverse(next), then print current character  

### 4. Sum of Natural Numbers
- Input n  
- If n ≤ 1 → return 1  
- Else → return n + sum(n-1)  

---



