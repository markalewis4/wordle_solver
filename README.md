# wordle_solver
Attempts to solve the game Wordle in as few attempts possible, given valid solutions and valid guesses.

Evaluation, given word lists as of 2021-02-15...

AVERGAE GUESSES: 3.47 

GUESS DISTRIBUTION:
1. 0% (0)
2. 3.6% (83)
3. 47.7% (1104)
4. 46.6% (1079)
5. 2.1% (49)

Alrgorithm explained...

- After a guess, we can create a list of remaining possible solutions (RPS), given the results of the guess and the RPS before the guess.
- We will choose the guess that minimizes the expected number of RPS (averaging number of RPS for each potential result from a guess).

Spoilers...
- The best starting guess is 'ROATE'.
- ROATE results in an expected RPS of 60.42 solutions. 

To solve a wordle...
- Follow the instructions in the Jupyter Notebook.
