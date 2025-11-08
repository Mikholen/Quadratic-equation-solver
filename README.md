## Introduction
The problem of solving quadratic equations arises everywhere, it is well studied and does not cause difficulties. Therefore, to start with the C programming language, it was decided to implement a quadratic equation solver. The quadratic equation has the following general form $$ax^2 + bx + c = 0$$, where $a \neq 0$, in case if $a = 0$, the quadratic equation turns into a linear one. If $a = 0$, the equation may have a solution, but the equation can no longer be considered quadratic, however, this case is handled in the proposed project and will not cause errors or unexpected behaviour. Let's return to the general form of the quadratic equation. To solve the equation or prove the absence of solutions, the discriminant is calculated using the formula $$D = b^2 - 4ac$$. For $D > 0$, the equation has 2 real solutions, for $D = 0$, the equation has 1 solution, for $D < 0$, the equation has no real solutions, and it always has 2 complex solutions. If the quadratic equation has turned into a linear one at $c != 0$ it is guaranteed to have 1 solution, for $b = 0, c = 0$ the equation has an infinite number of solutions, for $b = 0$ and $c != 0$ the equation has no solutions.

## Solution
This repository provides an implementation of a quadratic equation solver. Previously, before launching the program, tests are run, in case of successful completion of which it is proposed to enter the coefficients $a$, $b$ and $c$ of the quadratic equation. After entering the coefficients, the program will output the roots, if any, or send a message stating that there are no roots. The program does not support working with complex numbers, therefore, in the case of a negative discriminant, a message about the absence of real roots will be displayed. 

## Run the program
### Run
1) Clone the repository
```shell
git clone ...
```
2) Go to repository folder
```bash
cd Quadratic-equation-solver
```
3) Assemble the project
```bash
make
```
4) Run the executable file
```bash
./final
```