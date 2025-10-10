# Challenge Name
scripting with arguments

## My solve
**Flag:** `pwn.college{s6pNZ9ahZH2_qjVieTjqRQdNC2f.0VNzMDOxwyM3EzNzEzW}`

```bash
Connected!
hacker@chaining~scripting-with-arguments:~$ printf '%s\n' '#!/bin/bash' '' 'echo "$2 $1"' > /home/hacker/solve.sh
hacker@chaining~scripting-with-arguments:~$ chmod +x /home/hacker/solve.sh
hacker@chaining~scripting-with-arguments:~$ /challenge/run
Correct! Your script properly reversed the arguments.
Here's your flag:
pwn.college{s6pNZ9ahZH2_qjVieTjqRQdNC2f.0VNzMDOxwyM3EzNzEzW}
```

## Incorrect tangents I went on
none

## What I learned
i learnt about arguments in shell scripts.

## References 
None
