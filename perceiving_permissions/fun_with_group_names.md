# Challenge Name
fun with group names

## My solve
**Flag:** `pwn.college{ojhev1bon1ETZKkBw7yK1gWHFXU.QXycjM1wyM3EzNzEzW}`

```bash
Connected!
hacker@permissions~fun-with-groups-names:~$ id
uid=1000(hacker) gid=1000(grp18250) groups=1000(grp18250)
hacker@permissions~fun-with-groups-names:~$ ls -l
total 36
-rw-r--r-- 1 hacker grp18250   4 Sep 27 18:25 COLLEGE
-rw-r--r-- 1 hacker grp18250   8 Sep 28 17:06 PWN
-rw-r--r-- 1 root   grp18250  60 Sep 23 15:17 a
-rw-r--r-- 1 hacker root      60 Sep 24 14:52 flag
-rw-r--r-- 1 hacker grp18250 829 Sep 28 16:58 instructions
-rw-r--r-- 1 hacker grp18250  95 Sep 28 16:58 myflag
lrwxrwxrwx 1 hacker grp18250   5 Sep 27 14:29 not-the-flag -> /flag
-rw-r--r-- 1 root   grp18250  77 Sep 28 17:42 pwn_output
-rw-r--r-- 1 hacker grp18250 437 Sep 27 18:50 the-flag
hacker@permissions~fun-with-groups-names:~$ chgrp grp18250 /flag
hacker@permissions~fun-with-groups-names:~$ cat /flag
pwn.college{ojhev1bon1ETZKkBw7yK1gWHFXU.QXycjM1wyM3EzNzEzW}
```
## Incorrect tangents I went on
None

## What I learned
I learnt more about group names.

## References 
None
