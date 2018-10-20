# Tutorial 2
## Code
```
LINK 800
GRAB 200
ADDI F X X
ADDI F X X
MULI F X X
SUBI X F F
LINK 800
```

## Performance
| Cycles | Size | Activity |
|--------|------|----------|
|   8    |   7  |     2    |

## Discussion
Goes to where the file is, gets it, does the required math, and moves it to the Outbox.
Similar to Tutorial 1, when the Exa runs out of instructions, it drops the file and self-destructs so we don't have to explicitly do either of those.
