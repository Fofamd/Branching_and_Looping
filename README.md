# Branching and Looping Assignment (Java)

This repository contains the completed solutions for the 8 Java programming assignment problems covering **Branching** (decision-making) and **Looping** (repetition).

---

## Assignment Checklist (8/8 Completed)

| Part | # | Program | Source File | Description |
|:---:|:---:|:---|:---|:---|
| **Branching** | 1 | Even or Odd | [`EvenOdd.java`](file:///c:/Users/DELL/Downloads/Branching_and_Looping/EvenOdd.java) | Determines if a number is even or odd using `% 2`. |
| **Branching** | 2 | Exam Result | [`ExamResult.java`](file:///c:/Users/DELL/Downloads/Branching_and_Looping/ExamResult.java) | Evaluates whether a score is $\ge 70$ (Passed) or Failed. |
| **Branching** | 3 | Largest of Three Numbers | [`LargestNumber.java`](file:///c:/Users/DELL/Downloads/Branching_and_Looping/LargestNumber.java) | Finds the maximum of three numbers or checks if all are equal. |
| **Branching** | 4 | Time-of-Day Greeting | [`Greeting.java`](file:///c:/Users/DELL/Downloads/Branching_and_Looping/Greeting.java) | Outputs a greeting based on hour (0–23) or reports an invalid hour. |
| **Looping** | 5 | Alphabet Printer | [`AlphabetPrinter.java`](file:///c:/Users/DELL/Downloads/Branching_and_Looping/AlphabetPrinter.java) | Prints the first $N$ capital letters (A–Z) using character arithmetic. |
| **Looping** | 6 | Powers of Two | [`PowersOfTwo.java`](file:///c:/Users/DELL/Downloads/Branching_and_Looping/PowersOfTwo.java) | Computes and displays $2^0$ through $2^N$ without using `Math.pow()`. |
| **Looping** | 7 | Vowel Counter | [`VowelCounter.java`](file:///c:/Users/DELL/Downloads/Branching_and_Looping/VowelCounter.java) | Iterates through a string and counts all vowels (`a`, `e`, `i`, `o`, `u`). |
| **Looping** | 8 | Fibonacci Sequence | [`Fibonacci.java`](file:///c:/Users/DELL/Downloads/Branching_and_Looping/Fibonacci.java) | Prints the first $N$ terms in the Fibonacci series. |

---

## How to Run in VS Code

1. Open the folder `Branching_and_Looping` in **VS Code**.
2. Open any `.java` file (e.g. `EvenOdd.java`).
3. Click the **Run** button (play icon at the top right) or press `F5` / `Ctrl + F5`.
4. Enter input values when prompted in the terminal.

---

## How to Run via Terminal / Command Prompt

You can run any single file directly with Java 11+ without manual compilation:

```powershell
java EvenOdd.java
java ExamResult.java
java LargestNumber.java
java Greeting.java
java AlphabetPrinter.java
java PowersOfTwo.java
java VowelCounter.java
java Fibonacci.java
```

Or using standard compilation:

```powershell
javac EvenOdd.java
java EvenOdd
```

---

## Program Details & Example Test Cases

### 1. Even or Odd (`EvenOdd.java`)
- **Question**: Input a number. If it can be divided by 2, print `Even Number`. Otherwise, print `Odd Number`.
- **Sample Run**:
  ```text
  Enter a number: 8
  Even Number
  ```

### 2. Exam Result (`ExamResult.java`)
- **Question**: Input an exam score. If the score is 70 or higher, print `Passed`. Otherwise, print `Failed`.
- **Sample Run**:
  ```text
  Enter your score: 85
  Passed
  ```

### 3. Largest of Three Numbers (`LargestNumber.java`)
- **Question**: Input three numbers and print the largest. If all three are equal, print `All Numbers Are Equal`.
- **Sample Run**:
  ```text
  Enter first number: 10
  Enter second number: 25
  Enter third number: 15
  Largest = 25
  ```

### 4. Time-of-Day Greeting (`Greeting.java`)
- **Question**: Input an hour from 0 to 23. Print a greeting based on the hour:
  - `5` to `11`: Good Morning
  - `12` to `17`: Good Afternoon
  - `18` to `21`: Good Evening
  - `22` to `4`: Good Night
  - `< 0` or `> 23`: Invalid Hour
- **Sample Run**:
  ```text
  Enter hour (0-23): 9
  Good Morning
  ```

### 5. Alphabet Printer (`AlphabetPrinter.java`)
- **Question**: Input a number from 1 to 26. Print the first $N$ capital letters of the alphabet using a loop.
- **Sample Run**:
  ```text
  Enter a number (1-26): 5
  A B C D E
  ```

### 6. Powers of Two (`PowersOfTwo.java`)
- **Question**: Print powers of 2 from $2^0$ up to $2^N$. Do not use `Math.pow()`.
- **Sample Run**:
  ```text
  Enter N: 6
  1 2 4 8 16 32 64
  ```

### 7. Vowel Counter (`VowelCounter.java`)
- **Question**: Input a sentence and count how many vowels it contains. Count both uppercase and lowercase vowels.
- **Sample Run**:
  ```text
  Enter a sentence: Programming is fun
  Vowels = 5
  ```

### 8. Fibonacci Sequence (`Fibonacci.java`)
- **Question**: Print the first $N$ Fibonacci numbers. Each number is the sum of the previous two numbers ($0, 1, 1, 2, 3, 5, \dots$).
- **Sample Run**:
  ```text
  Enter N: 8
  0 1 1 2 3 5 8 13
  ```
