# Coding for Innovators

A collection of Python practice programs: coding exercises, file handling, small Tkinter GUI apps and a Turtle drawing.

## Contents

| Folder | Programs |
|---|---|
| `assignment2/` | `program1.py` sums the multiples of 3 or 5 below a number. `program2.py` converts dash or underscore separated text to camelCase. `program3.py` removes vowels from a string. `program4.py` sorts the words of a sentence by the number inside each word. `program5.py` sorts the odd numbers in a list. |
| `codewars/` | `program3.py` has solutions to two Codewars-style exercises: removing `!` from a string and `dig_pow(n, p)`. |
| `filehandling/` | `program1.py` writes and reads a text file (`ai.txt`). `program2.py` copies a binary file (`test.jpeg` to `testoutput.jpeg`). |
| `tkinderprograms/` | `groq_chatbot.py` is a Tkinter chatbot that uses the Groq API. `lovecalculator.py` is a Tkinter "Love Calculator". |
| `turtleprograms/` | `Ironman.py` draws a figure with Python's `turtle` module. |

## Run

Each file is a standalone script:

```bash
python assignment2/program1.py
```

`tkinderprograms/groq_chatbot.py` needs `pip install groq python-dotenv` and a `.env` file with `GROQ_API_KEY`.
