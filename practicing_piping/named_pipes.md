# Challenge Name
Named pipes

## My solve
**Flag:** `pwn.college{UXD8KhTnY_bwVUJra6HxwcNFvcP.QX4YjM1wCM2gjNzEzW}`

```bash
TERMINAL 1:
Connected!
hacker@piping~named-pipes:~$ mkfifo /tmp/flag_fifo
hacker@piping~named-pipes:~$ /challenge/run > /tmp/flag_fifo
You're successfully redirecting /challenge/run to a FIFO at /tmp/flag_fifo!
Bash will now try to open the FIFO for writing, to pass it as the stdout of
/challenge/run. Recall that operations on FIFOs will *block* until both the
read side and the write side is open, so /challenge/run will not actually be
launched until you start reading from the FIFO!

TERMINAL 2:
Connected!
hacker@piping~named-pipes:~$ cat /tmp/flag_fifo
You've correctly redirected /challenge/run's stdout to a FIFO at
/tmp/flag_fifo! Here is your flag:
pwn.college{4rsPZSliI5UBAR-RlHcHuUCQka1.01MzMDOxwyM3EzNzEzW}
```
## Incorrect tangents I went on
None

## What I learned
I learned how to use the mkfifo command to create persistent pipes.

## References 
None
