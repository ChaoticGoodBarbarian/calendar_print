Print Calendar

Time limit: 1 second
Memory limit: 64 MB
Input: standard input or input.txt
Output: standard output or output.txt

You are given two integers:
n — the weekday of the 1st day of the month (1 = Monday, 2 = Tuesday, ..., 7 = Sunday)
k — the number of days in the month (1 ≤ k ≤ 99)

Print the calendar for this month.

Example for n = 7, k = 31 (1st day falls on Sunday):

                   1
 2  3  4  5  6  7  8
 9 10 11 12 13 14 15
16 17 18 19 20 21 22
23 24 25 26 27 28 29
30 31

Output rules:
- Each day number occupies exactly 2 characters (numbers 1–9 are printed with a leading space: " 1", " 2", etc.)
- Exactly one space between numbers in the same row
- The first row may have leading spaces so that the 1st day appears in the correct column
- No trailing spaces at the end of any line
- The entire output must end with exactly one newline (no extra empty lines)

Input:
7 31

Output:
                   1
 2  3  4  5  6  7  8
 9 10 11 12 13 14 15
16 17 18 19 20 21 22
23 24 25 26 27 28 29
30 31
