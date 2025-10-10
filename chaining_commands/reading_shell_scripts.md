# Challenge Name
reading shell scripts

## My solve
**Flag:** `pwn.college{00h27j-PsF4CSyWmhRbjpITEWMB.0lMwgDOxwyM3EzNzEzW}`

```bash
Connected!
hacker@chaining~reading-shell-scripts:~$ cat /challenge/run
#!/opt/pwn.college/bash

read GUESS
if [ "$GUESS" == "hack the PLANET" ]
then
        echo "CORRECT! Your flag:"
        cat /flag
else
        echo "Read the /challenge/run file to figure out the correct password!"
fi
hacker@chaining~reading-shell-scripts:~$ /challenge/run
hack the PLANET
CORRECT! Your flag:
pwn.college{00h27j-PsF4CSyWmhRbjpITEWMB.0lMwgDOxwyM3EzNzEzW}
```

## Incorrect tangents I went on
none

## What I learned
i learnt how to read shell scripts.

## References 
None
