# Cpp_Exp_15_recursion

# Experiment-15: Recursion in C++

## 📌 AIM
To study and implement recursion in C++ through four different programs:
1. Factorial of a number  
2. Reverse digits of a number  
3. Reverse a string  
4. Sum of natural numbers  

---

## 🎯 OBJECTIVES
- Understand the principle of recursion and its working mechanism.  
- Learn how problems can be broken into smaller subproblems.  
- Differentiate recursion from iteration.  

---

## 📖 THEORY
**Recursion** is a programming technique where a function calls itself to solve a problem.  

- **Base Case:** Condition that stops recursion.  
- **Recursive Case:** Step that reduces the problem into smaller subproblems.  

**Types of Recursion:** Direct, Indirect, Tail, Head.  

**Pros:** Elegant, closer to math definitions, simplifies logic.  
**Cons:** More memory, slower, risk of stack overflow.  

---

## 🔍 PROGRAMS

### 1. Factorial of a Number
```cpp
int factorial(int n) {
    if (n <= 1) return 1;
    return n * factorial(n - 1);
}
