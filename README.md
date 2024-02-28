# Scheme

## What is this repository about?

In this project, I developed an interpreter for a subset of the Scheme language in Python.
It was a project, as part of the course [CS61A](https://cs61a.org/) at the University of California, Berkeley.
The overarching purpose of the project was to learn about the idea of abstraction.

## How is the repository structured?

- buffer.py: implements the Buffer class, used in scheme_reader.py; it assists in iterating through lines and tokens.
- questions.scm: contains some helper functions written in scheme
- scheme.py: implements the REPL (Read-Eval-Print-Loop) and evaluates Scheme expressions
- scheme_primitives.py: implements the primitives of the Scheme language
- scheme_reader.py: implements the reader for Scheme input
- scheme_tokens.py: implements the tokenizer for Scheme input
- tests.scm: a collection of test cases written in Scheme
- ucb.py: utility functions
- tests: a directory of tests written in Python