# Challenge Name
scripting with multiple conditions

## My solve
**Flag:** `pwn.college{s4s2ItFymCmiitOEBrKuPeO3AXK.0FOzMDOxwyM3EzNzEzW}`

```bash
hacker@chaining~scripting-with-multiple-conditions:~$ printf '#!/bin/bash\n\nif [ "$1" == "hack" ]; then\n  echo "the planet"\nelif [ "$1" == "pwn" ]; then\n  echo "college"\nelif [ "$1" == "learn" ]; then\n  echo "linux"\nelse\n  echo "unknown"\nfi\n' > /home/hacker/solve.sh
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
