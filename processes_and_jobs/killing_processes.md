# Challenge Name
killing processes

## My solve
**Flag:** `pwn.college{wSPxwq7oUZ-ZxA7gM9rO-LDIw-x.QXyQDO0wyM3EzNzEzW}`

```bash
Connected!
hacker@processes~killing-processes:~$ ps -ef | grep dont_run
hacker       136     135  0 05:46 ?        00:00:00 /challenge/dont_run
hacker       159     145  0 05:48 pts/0    00:00:00 grep --color=auto dont_run
hacker@processes~killing-processes:~$ kill 136
hacker@processes~killing-processes:~$ /challenge/run
Great job! Here is your payment:
pwn.college{wSPxwq7oUZ-ZxA7gM9rO-LDIw-x.QXyQDO0wyM3EzNzEzW}
```
## Incorrect tangents I went on
None

## What I learned
I learned how to kill processes.

## References 
None
