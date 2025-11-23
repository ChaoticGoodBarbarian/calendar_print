```markdown
# Print Calendar

**Time limit:** 1 second  
**Memory limit:** 64 MB  
**Input:** standard input or `input.txt`  
**Output:** standard output or `output.txt`

## Description

You are given two integers:  
- `n` — the weekday of the 1st day of the month (1 = Monday, 2 = Tuesday, ..., 7 = Sunday)  
- `k` — the number of days in the month (1 ≤ k ≤ 99, not necessarily a real month)

Print the calendar exactly in the required format.

### Example (n = 7, k = 31 → 1st day is Sunday)

```text
                   1
 2  3  4  5  6  7  8
 9 10 11 12 13 14 15
16 17 18 19 20 21 22
23 24 25 26 27 28 29
30 31
```

## Input

Two integers `n` and `k` on a single line.

## Output requirements

- Each day number takes **exactly 2 characters** (right-aligned: numbers 1–9 are printed as `" 1"`, `" 2"`, etc.)
- Exactly **one space** between numbers in the same row
- The first row may contain leading spaces so that day 1 starts in the correct column
- **No trailing spaces** at the end of any line
- The whole output must end with **exactly one newline** (`\n`)

### Sample Input

```
7 31
```

### Sample Output

```text
                   1
 2  3  4  5  6  7  8
 9 10 11 12 13 14 15
16 17 18 19 20 21 22
23 24 25 26 27 28 29
30 31
```

Good luck and happy coding!
```

