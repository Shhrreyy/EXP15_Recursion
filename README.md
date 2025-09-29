# 🔁 EXP-15: Recursion in C++

## 🎯 Aim

To implement and understand the concept of **recursion** in C++ by solving problems like:  
1. Finding the factorial of a number.  
2. Adding numbers up to `n`.  
3. Reversing a string.  

---

## 📚 Theory

- **Recursion**  
  Recursion is a programming technique where a function **calls itself** directly or indirectly until a base condition is met.  

- **Key Concepts:**  
  1. **Base Case** – The condition where recursion stops.  
  2. **Recursive Case** – The part of the function where it calls itself with modified parameters.  

- **Examples:**  
  - Factorial `n! = n × (n-1)!`  
  - Sum of numbers `sum(n) = n + sum(n-1)`  
  - Reverse of string: Swap/recurse from both ends until the string is reversed.  

---

## 🧮 Algorithms / Steps

### a) **Factorial using Recursion**
1. Define a function `fact(n)`.  
2. Base Case → if `n == 0 or n == 1`, return 1.  
3. Recursive Case → return `n * fact(n-1)`.  
4. Call the function with a user-provided number.  

### b) **Sum of Numbers till n**
1. Define a function `sum(n)`.  
2. Base Case → if `n == 0`, return 0.  
3. Recursive Case → return `n + sum(n-1)`.  
4. Call the function with a user-provided `n`.  

### c) **Reverse a String**
1. Define a function `reverse(str, start, end)`.  
2. Base Case → if `start >= end`, stop recursion.  
3. Recursive Case → swap `str[start]` and `str[end]`, then call reverse for `start+1` and `end-1`.  
4. Print the reversed string.  

---

## ✅ Conclusion

- Recursion simplifies solving problems that can be broken into smaller, similar sub-problems.  
- Factorial demonstrates **mathematical recursion**.  
- Summation shows recursion for **series problems**.  
- String reversal shows recursion applied in **string manipulation**.  
- However, recursion must always have a **base case** to avoid infinite loops and stack overflow.  

---

## 🧵 Topics Covered

- Concept of Recursion  
- Base Case and Recursive Case  
- Factorial Calculation using Recursion  
- Summation of Natural Numbers using Recursion  
- String Reversal using Recursion  
