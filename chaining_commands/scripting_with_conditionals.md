# Challenge Name
scripting with conditonals

## My solve
**Flag:** `pwn.college{Q5Z6VMkKB5P91zBYN4NO6Vaqy07.0lNzMDOxwyM3EzNzEzW}`

```bash
Connected!
hacker@chaining~scripting-with-conditionals:~$ printf '%s\n' '#!/bin/bash' '' 'if [ "$1" = "pwn" ]' 'then' '  echo "college"' 'fi' > /home/hacker/solve.sh
hacker@chaining~scripting-with-conditionals:~$ chmod +x /home/hacker/solve.sh
hacker@chaining~scripting-with-conditionals:~$ /challenge/run
Correct! Your script properly handles all the conditions.
Here's your flag:
pwn.college{Q5Z6VMkKB5P91zBYN4NO6Vaqy07.0lNzMDOxwyM3EzNzEzW}
```

## Incorrect tangents I went on
none

## What I learned
i learnt how to involve conditional statements in shell script.

## References 
None
