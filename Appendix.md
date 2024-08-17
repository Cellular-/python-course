# Executing Python Code

***Assumes Python is installed on the device***
## REPL

### Description

The REPL (read, evaluate, print, loop) is a tool provided by the Python interpreter and takes a single user's input, evaluates it, prints results to the terminal then waits (loop) for the next input from the user. The REPL will ask for new instructions from the user until the user exits.
### Usage

The REPL is accessed by opening a terminal and entering the command `python` or `python3`. The REPL is closed by exiting the terminal or commonly using `CTRL+D`, `CTRL+C` or entering the command `exit()`. For example:

`> python` or `> python3`

You should then see something like this:

```
> python3
Python 3.11.4 (main, Jul 25 2023, 17:35:35) [Clang 14.0.0 (clang-1400.0.29.202)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> [Type your python commands here]
```
## Using the terminal

### Description

The terminal refers to any command-line interface. This is synonymous with typing in text then running the commands.
### Usage

On most computers, a terminal tool is offered. For Windows, you might search for the programs `cmd` or `PowerShell` and run them. For Linux and MacOS, you could search for the program `terminal` and run it.

Once you have a terminal open (and Python installed), you can run a Python script like so:

```python
# another_script.py

first_word = 'hello'
second_word = 'world'

print(first_word)
print(second_word)
```

To run:

```
> python3 another_script.py
> hello
> world
```
## Online Interpreters

Links:
https://www.programiz.com/python-programming/online-compiler/
# Symbols for this course

`>` - represents an open terminal (command line)
# Python Architecture

## Interpreter

The component of Python that takes your Python scripts and executes them on your machine.

## Built-in functions

### `print()`

The `print()` function is built into Python and comes with *almost* every Python version. It is used to display text to the terminal.
# Programming Languages

## High-Level

"Further away" from the CPU. High-level languages abstract away the complexities of programming hardware directly allowing you to focus on writing software.
## General Purpose

Used for multiple purposes. Unlike other programming languages like R which are specialized for math and data science.
## Interpreted vs Compiled

Here's an analogy. Let's say you are to give a speech in front of an audience. In one scenario, you are asked to read the speech from a teleprompter and are not required to practice the speech beforehand.

In the other scenario, you are required to practice the speech thoroughly before being allowed to speak in front of the audience.

In the first scenario, the advantage is that you don't have to invest time practicing beforehand. You can just start the teleprompter and go, but that means you might make more mistakes. This is like an interpreted programming language.

In the second scenario, since you were required to thoroughly practice the speech, you should make fewer mistakes. You may be able to get through the speech quicker as well since you are not limited by the speed of the teleprompter. This is like a compiled programming language.
## Dynamically typed

In simplified terms, a dynamically typed programming language check its variables against its typed at [[Appendix#Other#Run-time|run-time]].
## Type inference

The ability for a programming language to figure out a variables type from its value. For example:

```python
# somescript.py

my_variable = 'hello'
my_variable_2 = "hello"
```

The Python interpreter will "infer" that `my_variable` and `my_variable_2` are of type `str` (string).

In contrast, the Java programming language does not support type inference. For example:

```java

String myString = "hello";

```

Notice, I had to specify that the variable `myString` is of type `String`.

## Mutability

Refers to an object's ability, list a list or dictionary, to be changed after creation.

## Type casting

To convert an object of one type to another. For example:

```python
# cast_int_to_str.py

age = 25
age = str(age)
print(age)
```
# Other

## Syntax Highlighting

A feature of text editors called syntax highlighting. It works by scanning the text in a text file then applying different colors to each symbol.
## Run-time

When code is actually running on a machine. Do not confuse it with `runtime` which is a general term for all of the components required to execute programming language code.