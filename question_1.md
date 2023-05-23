# Question:

### Consider 5 boxes with the following values:

```text
Box 1 = 3
Box 2 = 7
Box 3 = 2
Box 4 = 5
Box 5 = 4
```

### Now follow the instructions:

1. Subtract the number in Box 3 from the number in Box 1, and put the result in Box 1.
2. Multiply the numbers in Box 2 and Box 4, and put the result in Box 2.
3. Add the numbers from Box 1 and Box 2, and put the result in Box 3.
4. If the number in Box 3 is greater than the number in Box 5, go to Step 5. Otherwise, go to Step 6.
5. Divide the number in Box 5 by the number in Box 3, and put the result in Box 4.
6. Subtract the number in Box 2 from the number in Box 4, and put the result in Box 5.

`What number is in Box 5 now?`

### Solve Problem

```mathematica
   Start
    |
    V
Box 3 - Box 1 --> Box 1   (Subtract the number in Box 3 from the number in Box 1, put the result in Box 1)
    |
    V
Box 2 * Box 4 --> Box 2   (Multiply the numbers in Box 2 and Box 4, put the result in Box 2)
    |
    V
Box 1 + Box 2 --> Box 3   (Add the numbers from Box 1 and Box 2, put the result in Box 3)
    |
    V
Box 3 > Box 5 ?          (Check if Box 3 is greater than Box 5)
 /      \
|        |
V        V
Yes      No
|        |
V        V
Box 5 / Box 3 --> Box 4   (Divide the number in Box 5 by the number in Box 3, put the result in Box 4)
    |
    V
Box 4 - Box 2 --> Box 5   (Subtract the number in Box 2 from the number in Box 4, put the result in Box 5)
    |
    V
   End
```