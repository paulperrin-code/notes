# Phase 1 – System Foundations

## Resources

* CS50x Introduction to Computer Science by Harvard
* MIT Missing Semester

## What I Learned

---

### Week 0 – Scratch

With Week 0 of CS50x, I learned topics in computer science like data, binary, and algorithms. I knew these words before, but not what they really meant. Computer science is about solving problems using computers: we give input, the computer processes it with logic and math, and then it produces output.

For “problem solving,” I understand it as finding a solution in a way a computer can understand and run. If we have an idea of the output, we need to figure out what the input and steps should be. We write those steps in a programming language, for example Python, C, or Java.

Data is information that computers store as bits (0 and 1), using on and off states in hardware. The computer handles these bits as numbers, and we decide what the numbers actually represent.

Algorithms are the step-by-step instructions that the computer follows to solve a problem. It’s a big topic, and I’m still learning the details.

---

### Week 1 – C

Now with Week 1 of CS50x, it goes into a specific programming language: C.  
`printf("Hello, world!");` is the first example, one of the classic beginner programs. C is an older language, but with the CS50 setup in VS Code, the basics like variables, conditionals, operators, and loops were not too hard. I already knew a bit of JavaScript, so even if the syntax is different, the logic is almost the same. I understand these concepts better now, and the lectures by Professor Malan were very clear. Many things I already saw before, but I’m reviewing each element:

* **Data Types** in C define the kind of data a variable stores (like integers, characters, or real numbers). This decides how much memory it uses and what values it can represent.

* **Operators** in C do actions on values. Arithmetic operators (+, -, *, /, %) handle math. Update operators like `+=` or `++` change values quickly. Boolean operators compare values to get true or false, so programs can make decisions.

* **Conditional Statements** in C let the program choose different paths:
  * `if / else` for decisions,
  * `switch` for checking specific values,
  * the ternary operator `?:` for very short conditions.

* **Loops** run code repeatedly:
  * `while` repeats while a condition is true,
  * `do while` repeats at least once before checking the condition,
  * `for` repeats a specific number of times, like counting with a loop variable.

* **Command-line basics** in Linux let me manage files by commands:
  * `ls` to list,
  * `cd` to move around,
  * `mkdir` to create folders,
  * `cp` to copy,
  * `rm` to delete,
  * `mv` to rename or move.

* **Magic numbers** are random hard-coded values with no explanation. Instead of putting `23` or `52` everywhere and hoping anyone remembers why, we define clear constants with `#define`. That makes the code readable, consistent, and prevents accidental changes.

---

### Week 2 – Arrays

In Week 2 of CS50x, I dove into how programs really work under the hood: functions, variable scope, arrays, debugging tools, and command-line arguments. A lot of stuff felt new, but now I can see how it all fits together.

* **Functions**: These let you bundle code into smaller pieces. You write a function so you don’t repeat yourself. You call it when you need it. This makes the code clearer.

* **Variables & Scope**: Variables store data. Scope means where a variable is valid (inside a function, outside, etc.). If you use a variable outside its scope, you get errors or weird behavior.

* **Debugging**: Not just “fix errors,” but using tools (like `printf` inspections or stepping through code) to find out *why* something went wrong. I learned how to pause code, inspect values, see “garbage” memory, and trace loops.

* **Arrays**: Instead of making `score1`, `score2`, `score3`, you use an array (e.g. `scores[3]`) to store values of the same type in a contiguous block. Zero-based indexing (`scores[0]` is the first value) matters.

* **Command-line arguments**: When running a program, you can give extra inputs (arguments) directly in the terminal, like `./program arg1 arg2`. They are handled before the program even starts running.

---

More to come as I continue CS50x and MIT Missing Semester.