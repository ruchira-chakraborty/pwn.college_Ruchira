# Challenge Name
suspending processes

## My solve
**Flag:** `pwn.college{8J6eiXtPyVlBVC7AQYUUpJJYL2L.QX1QDO0wyM3EzNzEzW}`

```bash
Connected!
hacker@processes~suspending-processes:~$ /challenge/run
I'll only give you the flag if there's already another copy of me running in
this terminal... Let's check!

UID          PID    PPID  C STIME TTY          TIME CMD
root         138     129  0 06:11 pts/0    00:00:00 bash /challenge/run
root         140     138  0 06:11 pts/0    00:00:00 ps -f

I don't see a second me!

To pass this level, you need to suspend me and launch me again! You can
background me with Ctrl-Z or, if you're not ready to do that for whatever
reason, just hit Enter and I'll exit!
^Z
[1]+  Stopped                 /challenge/run
hacker@processes~suspending-processes:~$ /challenge/run
I'll only give you the flag if there's already another copy of me running in
this terminal... Let's check!

UID          PID    PPID  C STIME TTY          TIME CMD
root         138     129  0 06:11 pts/0    00:00:00 bash /challenge/run
root         145     129  0 06:11 pts/0    00:00:00 bash /challenge/run
root         147     145  0 06:11 pts/0    00:00:00 ps -f

Yay, I found another version of me! Here is the flag:
pwn.college{8J6eiXtPyVlBVC7AQYUUpJJYL2L.QX1QDO0wyM3EzNzEzW}
```
## Incorrect tangents I went on
None

## What I learned
I learned how to suspend processes

## References 
None
