# Challenge Name
scripting with multiple conditions

## My solve
**Flag:** `pwn.college{s4s2ItFymCmiitOEBrKuPeO3AXK.0FOzMDOxwyM3EzNzEzW}`

```bash
Connected!
hacker@chaining~scripting-with-multiple-conditions:~$ echo '#!/bin/bash' > /home/hacker/solve.sh
hacker@chaining~scripting-with-multiple-conditions:~$ echo 'if [ "$1" == "hack" ]; then' >> /home/hacker/solve.sh
hacker@chaining~scripting-with-multiple-conditions:~$ echo '    echo "the planet"' >> /home/hacker/solve.sh
hacker@chaining~scripting-with-multiple-conditions:~$ echo 'elif [ "$1" == "pwn" ]; then' >> /home/hacker/solve.sh
hacker@chaining~scripting-with-multiple-conditions:~$ echo '    echo "college"' >> /home/hacker/solve.sh
hacker@chaining~scripting-with-multiple-conditions:~$ echo 'elif [ "$1" == "learn" ]; then' >> /home/hacker/solve.sh
hacker@chaining~scripting-with-multiple-conditions:~$ echo '    echo "linux"' >> /home/hacker/solve.sh
hacker@chaining~scripting-with-multiple-conditions:~$ echo 'else' >> /home/hacker/solve.sh
hacker@chaining~scripting-with-multiple-conditions:~$ echo '    echo "unknown"' >> /home/hacker/solve.sh
hacker@chaining~scripting-with-multiple-conditions:~$ echo 'fi' >> /home/hacker/solve.sh
hacker@chaining~scripting-with-multiple-conditions:~$ chmod +x /home/hacker/solve.sh
hacker@chaining~scripting-with-multiple-conditions:~$ /challenge/run
Correct! Your script properly handles all the conditions with elif.
Here's your flag:
pwn.college{s4s2ItFymCmiitOEBrKuPeO3AXK.0FOzMDOxwyM3EzNzEzW}
```

## Incorrect tangents I went on
none

## What I learned
i learnt how to use elif command.

## References 
None
