# flow-graph-aptitude-test
The Flow Graph Aptitude Test assesses logical reasoning and problem-solving skills by evaluating the ability to interpret and analyze flowcharts or diagrams, identifying patterns, making connections, and understanding sequential processes.
`
## `Create from Template`

### Set Template

```
from this template

Consider 8 boxes with following values
Box 1 = 2
Box 2 = 7
Box 3 = 2
Box 4 = 1
Box 5 = 5
Box 6 = 7
Box 7 = 1
Box 8 = 4

Now follow the instructions:

1. Put the number from Box 7 into Box 1
2. Add the numbers from Box 1 and Box 2, and put the result in Box 1
3. Change Instruction 2, Increase the number in Box 2 by 1
4. If the second box number mentioned in instruction 2 is greater than the number in box 8, stop. If not, go to step 2.

What number is in Box 1 now?

Note: When you are told to put a number into a box, it is understood that whatever number was previously in that box has just been erased.
```

### Generate

```
Create new question Flow Graph Aptitude Test reference question above
```

## `Create from Prompt`

### Prompt

```
1. Random number of boxes between 5 - 8 [n]
2. Add string "You are given [n] boxes with the following values:"
3. Random number between 1 - 9 assigned to each box [x] and show following this template
'''
Box 1 = [x]
Box 2 = [x]
Box [n] = [x]
'''
4. Random number of instructions between 5 [i]
5. Add string "Now follow the [i] instructions:"
6. Random instruction use operation in (Add, Subtract, Move, Increase) and show following this template
'''
1. Add the numbers from Box 1 and Box 2
2. Increase the number in Box 2 by 1
'''
7. Random number of boxes for question [y]
8. Add string "What number is in Box [y] now?"
```