# CMPS 2200  Recitation 01

In this recitation, we will investigate asymptotic complexity. 

To complete this recitation, follow the instructions in [recitation-01.md](recitation-01.md). Below you'll find important and useful information about submitting your work, using git, and testing your code. 

## Turning in your work
- You may work with a partner to complete this recitation.
- Only one team member needs to push your completed lab to github. 
- At the top of `main.py` and in the `answers.md` file, **include the names of both** team members.
- Once you have pushed your final submission to GitHub, go to Canvas and submit a link to your repository to the Canvas assignment for this recitation. 
  - Submit to Canvas in group with your partner.

## Using Git 
- [Clone] your Recitation 01 repository to your local device.
- As you complete this lab, `add`, `commit`, and `push` your work up to GitHub. 
  - You will need to issue `git add` for all files that you have modified, e.g., `main.py`, `answers.md`, and any others that you modify or add to the repository as well.
  - For example, on the command line, in the same directory as your cloned lab:
    ```
    $ git add main.py
    $ git add answers.md
    $ git commit -m "Implement Required Functions, Answer all Questions"
    $ git push origin main
    ```
  - It is recommended that you `add`, `commit`, and `push` your work often in order to regularly save your work to GitHub. The latest version of your work will be what is graded.

## Running and testing your code
- You can run the tests using `pytest`. If you need to, install `pytest`. On your terminal:
  + `$ pip3 install pytest`
  + You may also have to install other python modules such as `tabulate` or other imported modules as you work through these recitations.
- It's usually best to run only one test at a time. To run tests, from the command-line, execute:
  + `$ pytest main.py` to run all tests
  + `$ pytest main.py::test_binary_search` to just run `test_binary_search`
  + GitHub will test your code using `pytest`.
- If you want to run your whole program, make sure to use `python3`. `python` might still default to python version 2.

[Clone]: https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository-from-github/cloning-a-repository