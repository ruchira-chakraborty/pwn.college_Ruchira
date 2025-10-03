# Challenge Name
groups and file

## My solve
**Flag:** `pwn.college{4AI8m3lfvhDWkWR4_TgjwUjZQ9Y.QXxcjM1wyM3EzNzEzW}`

```bash
Connected!
hacker@permissions~groups-and-files:~$ ls -l
total 36
-rw-r--r-- 1 hacker hacker   4 Sep 27 18:25 COLLEGE
-rw-r--r-- 1 hacker hacker   8 Sep 28 17:06 PWN
-rw-r--r-- 1 root   hacker  60 Sep 23 15:17 a
-rw-r--r-- 1 hacker root    60 Sep 24 14:52 flag
-rw-r--r-- 1 hacker hacker 829 Sep 28 16:58 instructions
-rw-r--r-- 1 hacker hacker  95 Sep 28 16:58 myflag
lrwxrwxrwx 1 hacker hacker   5 Sep 27 14:29 not-the-flag -> /flag
-rw-r--r-- 1 root   hacker  77 Sep 28 17:42 pwn_output
-rw-r--r-- 1 hacker hacker 437 Sep 27 18:50 the-flag
hacker@permissions~groups-and-files:~$ chgrp hacker /flag
hacker@permissions~groups-and-files:~$ cat /flag
pwn.college{4AI8m3lfvhDWkWR4_TgjwUjZQ9Y.QXxcjM1wyM3EzNzEzW}
```
## Incorrect tangents I went on
None

## What I learned
I learned how to change group ownerships.

## References 
None
