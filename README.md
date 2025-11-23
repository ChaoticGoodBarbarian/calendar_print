```markdown
# Calendar Printing

**Time Limit:** 1 second  
**Memory Limit:** 64 MB  
**Input:** standard input or `input.txt`  
**Output:** standard output or `output.txt`  

Print a month layout based on the given starting weekday and the number of days.  
Your output should look approximately like this:

```

```
               1
```

2  3  4  5  6  7  8
9 10 11 12 13 14 15
16 17 18 19 20 21 22
23 24 25 26 27 28 29
30 31

```

## Input Format
Two integers are given:  
- **n** — the weekday number of the first day of the month (1 to 7),  
- **k** — the number of days in the month (1 to 99).  

It is guaranteed that **n ≤ k**.  
Note: the number of days does not have to match real calendar months.

## Output Format
Print the calendar exactly as in the example.  
- Empty positions in the first line must be filled with spaces.  
- Adjacent numbers are separated by a space.  
- Each number occupies exactly two characters.  
- Lines must not end with trailing spaces.  
- The output should end with exactly one newline.
```
