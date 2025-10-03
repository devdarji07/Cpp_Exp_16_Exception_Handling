# Cpp_Exp_16_Exception_Handling
# 🚀 Experiment-16: Exception Handling in C++

## 📌 AIM
To understand and implement exception handling in C++ using the `try`, `throw`, and `catch` mechanism through the following programs:
1. Division of two numbers (with division by zero check)  
2. Age validation (checking if the user is underage)  

---

## 🎯 OBJECTIVES
- To learn how C++ handles runtime errors gracefully.  
- To understand the use of `try`, `throw`, and `catch` blocks.  
- To practice throwing exceptions of different data types.  
- To explore exception handling as an alternative to traditional error handling.  
- To ensure program safety and reliability during abnormal situations.  

---

## 📖 THEORY

### 🔹 What is Exception Handling?
Exception handling is a mechanism to **detect and handle runtime errors** in a structured way.  
Instead of terminating the program abruptly, exceptions allow the program to *catch* the error and respond safely.  

### 🔹 Components
- **try block** → contains code that may throw an exception.  
- **throw statement** → signals that an exception has occurred.  
- **catch block** → handles the exception thrown by `throw`.  

### 🔹 Advantages
- Improves program reliability and security.  
- Separates error-handling code from normal logic.  
- Prevents crashes by handling runtime errors.  
- Allows multiple error types to be managed.  

---

## ⚖️ Exception Handling vs Normal Error Handling

| Feature             | Normal Error Handling (if-else) | Exception Handling (try-throw-catch) |
|---------------------|--------------------------------|--------------------------------------|
| Style               | Mixes error checks with logic  | Separates logic & error handling     |
| Flexibility         | Limited                        | Can handle multiple error types      |
| Runtime Errors      | May cause crash if unhandled   | Prevents crash by safe handling      |
| Readability         | Code may be lengthy/complex    | Cleaner and structured               |

---

## 📊 COMPARISON TABLE

| Program          | Exception Condition | Exception Type | Example Input  | Example Output            | Concept Focus             |
|------------------|---------------------|----------------|----------------|---------------------------|---------------------------|
| Division Program | If denominator = 0  | float          | n1 = 10, n2=0  | ERROR: Division by 0      | Mathematical error check  |
| Age Validation   | If age < 18         | int            | age = 15       | ERROR: Underage (15)      | Input validation          |

---

## 🧮 ALGORITHMS

### 1. Division Program (Division by Zero Check)
1. Input two numbers: numerator and denominator.  
2. Begin a try block.  
3. If denominator = 0 → throw an exception.  
4. Else → perform division and display result.  
5. In catch block → display error message.  

### 2. Age Validation Program
1. Input age.  
2. Begin a try block.  
3. If age < 18 → throw an exception.  
4. Else → display valid age and approval message.  
5. In catch block → display error message.  

---

## 💻 PROGRAMS

