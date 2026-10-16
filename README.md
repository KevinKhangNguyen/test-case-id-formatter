# Test-Case ID Formatter

## What it does
This tool takes inputs for a test case (module prefix, test number, title, and test execution numbers) and outputs a standardized, zero-padded test-case ID along with summary metrics including failures, pass rate, and a release decision.

## How to run
1. Open a terminal in the project folder.
2. Run the script using Python: python test_case_id_formatter.py

## Given Output
$ python check_exercise.py
=== Program checks (4 sample runs) ===
  PASS  Sample run: login / 42 / 34 of 40 passed
  PASS  Sample run: messy spaces, everything passed
  PASS  Sample run: rounding: 2 of 3 passed
  PASS  Sample run: exactly on the threshold and a 3-digit number

=== Git checks ===
  PASS  At least 3 commits
  PASS  Commit messages are specific
  PASS  Formatter file changed in 3+ commits
  PASS  Working tree clean (nothing left uncommitted)

=== Stretch goals (optional, do not affect the result) ===
  --    Stretch 1: Next ID line (not done)
  --    Stretch 2: ID length line (not done)

RESULT: all 8 checks passed. Paste this output into your submission.
