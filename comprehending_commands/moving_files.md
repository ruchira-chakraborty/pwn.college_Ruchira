# Challenge Name
moving files

## My solve
**Flag:** `pwn.college{wycSYozjOUt0kPYnByGSDzhR5qZ.0VOxEzNxwyM3EzNzEzW}`

```bash
Connected!
hacker@commands~moving-files:~$ ls
a  flag
hacker@commands~moving-files:~$ mv flag hack-the-planet
ERROR: please make sure that you specify the flag file (/flag)
as your SOURCE! (You specified /home/hacker/flag).
hacker@commands~moving-files:~$ mv /flag /tmp/hack-the-planet
Correct! Performing 'mv /flag /tmp/hack-the-planet'.
hacker@commands~moving-files:~$ /challenge/check
Congrats! You successfully moved the flag to /tmp/hack-the-planet! Here it is:
pwn.college{wycSYozjOUt0kPYnByGSDzhR5qZ.0VOxEzNxwyM3EzNzEzW}
```
## Incorrect tangents I went on
I did not specify the flag file source.

## What I learned
I learned how to move files using mv command.

## References 
None
