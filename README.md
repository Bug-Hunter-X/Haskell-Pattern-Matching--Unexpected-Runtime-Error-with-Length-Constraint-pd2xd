# Haskell Pattern Matching Bug: Length Constraint

This repository demonstrates a common error in Haskell involving pattern matching with explicit length constraints.  The `bug.hs` file contains code that attempts to match a list of exactly three elements. If a shorter list is passed, the program crashes with a `Non-exhaustive patterns` error at runtime.

The solution, `bugSolution.hs`, shows how to correctly handle cases where the input list might be shorter than expected using guards or more comprehensive patterns.