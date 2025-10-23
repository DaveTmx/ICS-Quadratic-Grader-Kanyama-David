# ICS-Quadratic-Grader-Kanyama-David
## Project Description
This project, developed for the ICT251 JS GitHub Activity, is a single-file web application (`index.html`) that implements two JavaScript-driven tools: a **Quadratic Equation Solver** and a **Grading System** calculator. The page runs entirely offline.

## Tools Implemented

### 1. Quadratic Solver
Calculates the discriminant, determines the nature of the roots (distinct real, equal real, or complex conjugate), and provides the value of the roots for any quadratic equation $ax^2 + bx + c = 0$. Includes validation for non-numeric input and the $a \neq 0$ condition.

### 2. Grading System
Converts a numerical score (0-100) into a letter grade based on defined thresholds (A+, A, B+, B, C+, C, D, F). Includes validation to ensure the score is within the required 0-100 range.

## Screenshots

*Insert a screenshot of your running `index.html` file here.*

## Test Cases

### Quadratic Solver Test Cases

| a | b | c | Expected Discriminant | Expected Nature of Roots | Expected Roots (approx) |
|---|---|---|---|---|---|
| 1 | -3 | 2 | 1 | Distinct Real | x1=2.0000, x2=1.0000 |
| 1 | -4 | 4 | 0 | Equal Real | x=2.0000 |
| 1 | 2 | 5 | -16 | Complex Conjugate | -1.0000 + 2.0000i, -1.0000 - 2.0000i |
| 0 | 5 | 1 | N/A | Error | "Error: 'a' cannot be zero..." |

### Grading System Test Cases

| Score | Expected Grade |
|---|---|
| 90 | A+ |
| 85 | A+ |
| 75 | A |
| 74 | B+ |
| 60 | B |
| 50 | C |
| 49 | D |
| 48 | F |
| -5 | Error |
| 101 | Error |
