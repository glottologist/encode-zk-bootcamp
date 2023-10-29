# Homework 9

## MINA - zkapps 2

### Questions

- 1). Does sudoku.ts solve the puzzle ?
- 2). Which lines in sudoku.ts indicate that a solution is
  correct
- 3). Is it possible to submit a correct solution, but have the
  proof rejected as false ?
- 4).If the prover altered the code, could they cheat and
  claim they had a solution, when in fact they didn't ?

### Answers

- 1). sudoku.ts confirms that a solution passed matches that os a sudoku instance passed. It confirms the following:
  - All rows contains the values 1 to 9
  - All columns contain the rows 1 to 9
  - Each 3x3 square contains the values 1 to 9
  - And that each square matches that of the solution passed OR IS ZERO.
  - Additionally checks that the hash matches that which was originally deployed.
- 2). sudoku.ts has a fall through confirmation. Each of the above clauses listed in 1) are checked. If all of those pass it then comes to the line:

```
      this.isSolved.set(Bool(true));
```

- 3). If a Sudoku puzzle is well formed it should have only one unique solution.  However, if not, there could exist multiple solutions to the same puzzle such that an alternative correct solution is rejected as it doesn't match teh expected solution even through it is valid. 
- 4). No, the hash check would show the code has been modified.  The check could be removed but then the zkApp would need to be deployed again so not match the original.
