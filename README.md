Let's start with a very simple example to understand how these exercises are going to work.

## How to solve a challenge

Your goal is to implement the function `sum3` in the `sum_of_three.py` file. The workflow you need to follow is:

1. Read all of the challenge instructions
1. Open the `sum_of_three.py` file where you need to write code and read it first
1. Run `make`
1. Read the first error message and try to make sense of it (if you need to, Google it!)
1. Change the code in `sum_of_three.py`
1. Re-run `pytest`
1. New error message? Less failures? You are making progress!
1. Repeat until you no longer have any errors
1. Make sure your style is correct and you achieve a `10.00/10` score
1. Commit & push your changes to Kitt:
  1. `git status` to check which files have been changed since the last commit
  1. `git diff` to check what has been changed
  1. `git add sum_of_three.py`
  1. `git commit -m "Solve first Python exercise of the day"`
  1. `git push origin master`


- [pytest](https://docs.pytest.org/en/latest/)

## Conclusion

The goal of this exercise is to show you how to run the tests to automatically evaluate your code (both style & correctness) and introduce you to this tight feedback loop.
