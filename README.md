# Python Projects & Games

A collection of small, self-contained Python exercises, each in its own notebook.
Written while practicing core language features (loops, string handling, file I/O,
basic encryption).

## Contents

- **Madlibs_Generator.ipynb** — reads `story.txt`, finds `<placeholder>` tags, prompts
  the user for words, and fills in a mad-libs style story. Note: the notebook reads
  the story from a hardcoded local file path, so it needs that path updated (or
  `story.txt` copied to a matching location) before it will run elsewhere.
- **Number Guessing Game.ipynb** — guess a random number within a user-chosen range,
  with attempt counting.
- **Password_Manger.ipynb** — a simple encrypted password store using
  `cryptography.fernet`; saves name/password pairs to a local text file, encrypted
  with a Fernet key. Requires a `key.key` file to exist (the key-generation code is
  present but commented out).
- **Quize_Game.ipynb** — a short multiple-question quiz about basic computer hardware
  acronyms (CPU, GPU, RAM, PSU), scored at the end.
- **Rock, Paper , Scissors.ipynb** — classic rock/paper/scissors against the computer,
  played in a loop with a running win tally.
- **Timed_Math_Challenge.ipynb** — generates 10 random arithmetic problems and times
  how long the user takes to answer them all correctly.

## Tech stack

- Python
- Jupyter Notebook
- `cryptography` (for the password manager)

## Running it

Each notebook is independent — open the one you want in Jupyter and run its cells.
They're all interactive, input()-driven console programs.
