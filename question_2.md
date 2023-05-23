# Question:

### Consider 6 boxes with the following values:

```text
Box 1 = 2
Box 2 = 5
Box 3 = 7
Box 4 = 3
Box 5 = 1
Box 6 = 4
```

### Now follow the instructions:

1. Add the numbers in Box 1 and Box 2, and put the result in Box 1.
2. Subtract the number in Box 3 from the number in Box 4, and put the result in Box 2.
3. Multiply the numbers in Box 5 and Box 6, and put the result in Box 3.
4. If the number in Box 1 is greater than the number in Box 2, go to Step 5. Otherwise, go to Step 6.
5. Add the numbers in Box 1 and Box 3, and put the result in Box 4.
6. Subtract the number in Box 2 from the number in Box 3, and put the result in Box 5.

`What number is in Box 5 now?`

### Solve Problem

```mathematica
   Start
    |
    V
Box 1 + Box 2 --> Box 1   (Add the numbers in Box 1 and Box 2, put the result in Box 1)
    |
    V
Box 4 - Box 3 --> Box 2   (Subtract the number in Box 3 from the number in Box 4, put the result in Box 2)
    |
    V
Box 5 * Box 6 --> Box 3   (Multiply the numbers in Box 5 and Box 6, put the result in Box 3)
    |
    V
Box 1 > Box 2 ?          (Check if Box 1 is greater than Box 2)
 /      \
|        |
V        V
Yes      No
|        |
V        V
Box 1 + Box 3 --> Box 4   (Add the numbers in Box 1 and Box 3, put the result in Box 4)
    |
    V
Box 3 - Box 2 --> Box 5   (Subtract the number in Box 2 from the number in Box 3, put the result in Box 5)
    |
    V
   End
```