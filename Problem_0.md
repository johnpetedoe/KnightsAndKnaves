00 All persons are either knights or knaves.
01 Knights only tell the truth.
02 Knaves only lie. 

03 Person's A and B say the following sentances:
0300 A: B is a knight
0301 B: I am not a knight

04 Is A a knight?

To solve this problem, we can start be representing it's truth table:

| A | B | {T, F, C} |
|---|---|-----------|
| T | T |           |
| T | F |           |
| F | T |           |
| T | T |           |

To solve this problem I will begin by translating each statement into a *formal language*.
This will allow us to remove ambiguity and solve the problem independent independently of it's interpretation like a math problem.

00   All persons are either knights or knaves.
00F  ```(:A (:x ($\in$))```
