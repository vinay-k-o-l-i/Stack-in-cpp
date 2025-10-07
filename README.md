# -StacksInCPP

# Experiment – Stacks in C++

**Student:** Rajendra Chaganti  
**PRN:** 24070123150  
**Batch:** B3  

---

## Aim  
To implement **Stack operations** (push, pop, display) using arrays in C++.

---

## Theory  

- A **Stack** is a linear data structure that follows the **LIFO (Last In, First Out)** principle.  
- Main operations:  
  - **Push** → Insert an element into the stack.  
  - **Pop** → Remove the top element from the stack.  
  - **Display** → Show all elements of the stack.  
- Stack overflow occurs when the stack is full and a new element is pushed.  
- Stack underflow occurs when trying to pop from an empty stack.  

---

## Algorithm  

1. Start the program.  
2. Define a class `Stack` with:  
   - Data members: array `arr[MAX]` and integer `top`.  
   - Functions: `push()`, `pop()`, `display()`.  
3. Initialize `top = -1`.  
4. In `push(val)`:  
   - If `top == MAX-1`, print **Stack Overflow**.  
   - Else increment `top` and insert value.  
5. In `pop()`:  
   - If `top == -1`, print **Stack Underflow**.  
   - Else decrement `top`.  
6. In `display()`:  
   - Print all elements from index `0` to `top`.  
7. In `main()`, perform multiple push, pop, and display operations.  
8. End the program.  

---

## Conclusion  

- Implemented **Stack operations** using arrays.  
- Understood stack properties: **Overflow** and **Underflow** conditions.  
- Learned LIFO principle and how to simulate it programmatically.  
