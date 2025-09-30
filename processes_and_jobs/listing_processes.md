# Challenge Name
listing processes

## My solve
**Flag:** `pwn.college{oaJKcw0pwL8NsYLtnbBN2Vbcbfy.QX4MDO0wyM3EzNzEzW}`

```bash
Connected!
hacker@processes~listing-processes:~$ ps -ef
UID          PID    PPID  C STIME TTY          TIME CMD
root           1       0  0 05:30 ?        00:00:00 /sbin/docker-init -- /nix/var/nix/profiles/dojo-workspace/bin/dojo-init /run/dojo/bin/sleep 6h
root           7       1  0 05:30 ?        00:00:00 /run/dojo/bin/sleep 6h
root         132       1  0 05:30 ?        00:00:00 /challenge/27656-run-16106
root         135     132  0 05:30 ?        00:00:00 sleep 6h
hacker       137       0  0 05:30 pts/0    00:00:00 /nix/store/0nxvi9r5ymdlr2p24rjj9qzyms72zld1-bash-interactive-5.2p37/bin/bash /run/dojo/bin/ssh-entrypoin
hacker       143     137  0 05:30 pts/0    00:00:00 /run/dojo/bin/bash --login
hacker       152     143  0 05:37 pts/0    00:00:00 ps -ef
hacker@processes~listing-processes:~$ /challenge/27656-run-16106
Yahaha, you found me! Here is your flag:
pwn.college{oaJKcw0pwL8NsYLtnbBN2Vbcbfy.QX4MDO0wyM3EzNzEzW}
Now I will sleep for a while (so that you could find me with 'ps').
```
## Incorrect tangents I went on
None

## What I learned
I learned how to list processes using ps command 

## References 
None
