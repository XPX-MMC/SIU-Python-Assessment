# SIU-Python-Assessment
Solve 3 problems in the `problems` folder. Test cases are provided in `main.py`. Work on the problems in their respective files, uncomment the appropriate test case(s) and run `main.py` or individual problem file to see if your solution is working. Follow the [Getting Started](#GettingStarted) section below and the [Completion](##Completion) section at the bottom of this README.

### Important
Do not use any LLMs or AI assistance of any sort. 
- You may refer to the official python documentation [https://docs.python.org/3/library/index.html] or the official git documentation [https://git-scm.com/doc] but do not search the internet for solutions or help. 
- This exercise is to determine your skills in solving problems and developing logic using Python.
- Do not alter the file structure
- To run a python file (in most IDEs), click the play button.

# Getting Started
1. Ensure Python 3 is installed on your device BEFORE BEGINNING ASSESSMENT. Use Fiserv Software Center for installation.
2. Fork and clone this repo - no branches, no PRs
3. Launch repo in your IDE of choice
4. Run the main file, you should see the following in your terminal output:

    ding dong
    who's there

## Challenge 1
In `pb1.py`, create a function, `replace_spaces`, that accepts two inputs:
- A string that represents a sentence
- The punctuation character that will replace the spaces in the sentence

Usage
```python
sentence = "Test  This is a test   Testing "
sentence2 = replace_spaces(sentence, "_")
print(sentence2)

```
Ouput:
```
Test__This_is_a_test__Testing_
```

## Challenge 2
In `pb2.py`, create a function, 'max_values' that given a list of numbers (positive or negative integers), it will return a list containing the indices of the two highest values. Order of the returned indices does not matter.

Usage
```python
print(max_values([4, 7, 2, 8, 10, 9]))
```
Output:
```
[4, 5]
```

## Challenge 3
In `pb3.py`, create a function, 'youngest_student', that takes a dictionary of student names and their ages as input 
and returns the name of the youngest student.

Usage:
```python
students = {"Alice": 18, "Bob": 20, "Charlie": 19, "David": 22, "Jay": 20}
print(youngest_student(students))
```

Output:
```
Alice
```

## Completion
Before time is up, git add, git commit and git push to YOUR FORK.
Do not create any Pull Requests.
