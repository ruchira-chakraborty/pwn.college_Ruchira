# Challenge Name
scripting with default cases

## My solve
**Flag:** `pwn.college{4YovyLaQD2zVqG7JE6REFZa_VTt.01NzMDOxwyM3EzNzEzW}`

```bash
Connected!
hacker@chaining~scripting-with-default-cases:~$ echo '#!/bin/bash' > /home/hacker/solve.sh
hacker@chaining~scripting-with-default-cases:~$ echo 'if [ "$1" == "pwn" ]; then' >> /home/hacker/solve.sh
hacker@chaining~scripting-with-default-cases:~$ echo '    echo "college"' >> /home/hacker/solve.sh
hacker@chaining~scripting-with-default-cases:~$ echo 'else' >> /home/hacker/solve.sh
hacker@chaining~scripting-with-default-cases:~$ echo '    echo "nope"' >> /home/hacker/solve.sh
hacker@chaining~scripting-with-default-cases:~$ echo 'fi' >> /home/hacker/solve.sh
hacker@chaining~scripting-with-default-cases:~$ chmod +x /home/hacker/solve.sh
hacker@chaining~scripting-with-default-cases:~$ /challenge/run
Correct! Your script properly handles the if/else conditions.
Here's your flag:
pwn.college{4YovyLaQD2zVqG7JE6REFZa_VTt.01NzMDOxwyM3EzNzEzW}
```

## Incorrect tangents I went on
none

## What I learned
i learnt how to if-else in shell scripts.

## References 
None
