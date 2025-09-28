# Challenge Name
duplicating piped data with tee

## My solve
**Flag:** `pwn.college{IjxroQulVMShZzgjbwk1B8es4rg.QXxITO0wyM3EzNzEzW}`

```bash
Connected!
plicating-piped-data-with-tee:~$ cat pwn_output
Usage: /challenge/pwn --secret [SECRET_ARG]

SECRET_ARG should be "IjxroQul"
hacker@piping~duplicating-piped-data-with-tee:~$ /challenge/pwn --secret IjxroQul
Processing...
You must pipe the output of /challenge/pwn into /challenge/college (or 'tee'
for debugging).
hacker@piping~duplicating-piped-data-with-tee:~$ /challenge/pwn --secret IjxroQul | /challenge/college
Processing...
Correct! Passing secret value to /challenge/college...
Great job! Here is your flag:
pwn.college{IjxroQulVMShZzgjbwk1B8es4rg.QXxITO0wyM3EzNzEzW}
```
## Incorrect tangents I went on
None

## What I learned
I learned how to duplicate data using tee command.

## References 
None
