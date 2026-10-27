# program design

Python notebooks from my Program Design module at TU Dublin. everything is a Jupyter notebook, so each lab runs one cell at a time and you can see what each piece of code does.

## what's in here

| notebook | what's in it |
|----------|--------------|
| `Lab1.ipynb` | getting used to Jupyter: printing, fixing a broken `print`, basic maths and variables |
| `Lab2.ipynb` | reading input, `if`/`elif`/`else`, and `while` loops: distance between two numbers, positive or negative, summing up to n, even or odd without `%`, and a guessing game with three tries |
| `Lab3PD.ipynb` | checking a range three different ways, loops that print odd numbers and count down, grading marks with `elif`, and a random multiplication quiz |
| `Lab4.ipynb` | sorting three numbers with only `if` statements, and a two-number guessing game using random numbers |
| `GradedLab.ipynb` | a longer lab with 11 questions on loops, conditionals and strings: leap years, averages, alternating sums, vowel counting, factorials, a countdown, and a lucky number game |

## running the notebooks

```bash
pip install notebook numpy
jupyter notebook
```

then open any `.ipynb` file. `Lab3PD` and `Lab4` use numpy for random numbers, which is why it's in the install line. VS Code with its Jupyter extension works too.
