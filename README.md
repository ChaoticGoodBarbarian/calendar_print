Вот готовый текст задачи на английском языке, полностью готовый для вставки в README.md (с правильным Markdown-оформлением, включая заголовок, ограничения, пример и форматирование кода):

```markdown
## Print Calendar

**Time limit:** 1 second  
**Memory limit:** 64 MB  
**Input:** standard input or input.txt  
**Output:** standard output or output.txt  

Print a calendar month given the starting day of the week and the number of days in the month. Your output should look like this:

```text
                   1
 2  3  4  5  6  7  8
 9 10 11 12 13 14 15
16 17 18 19 20 21 22
23 24 25 26 27 28 29
30 31
```

### Input
Two integers are given:
- `n` — the weekday number of the 1st day of the month (integer from 1 to 7, where 1 = Monday, 7 = Sunday)
- `k` — the number of days in the month (integer from 1 to 99)

It is guaranteed that `n ≤ k`.

Note: the number of days in the month does not have to match the real Gregorian calendar.

### Output
Print the calendar exactly as shown in the example:
- Each day number occupies exactly **2 characters** (right-aligned, padded with a space on the left if needed).
- Numbers in the same row are separated by a single space.
- The first row may contain leading spaces so that the 1st day starts in the correct column.
- There should be **no trailing spaces** at the end of any line.
- The output must end with **exactly one newline** (`\n`).

### Example

**Input:**
```
7 31
```

**Output:**
```
                   1
 2  3  4  5  6  7  8
 9 10 11 12 13 14 15
16 17 18 19 20 21 22
23 24 25 26 27 28 29
30 31
```
```

Просто скопируй этот блок в свой README.md — всё будет красиво отображаться на GitHub/GitLab и других платформах с поддержкой Markdown. Удачи в решении! 🚀
