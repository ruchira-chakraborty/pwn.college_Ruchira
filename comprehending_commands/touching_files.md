# Challenge Name
touching files

## My solve
**Flag:** `pwn.college{M7Ulhi3fkouCesg9Cb7ZneDBFcd.QXwMDO0wyM3EzNzEzW}`

```bash
Connected!
hacker@commands~touching-files:~$ cd /tmp
hacker@commands~touching-files:/tmp$ ls
bin  hsperfdata_root  tmp.TpSOPGOVKK
hacker@commands~touching-files:/tmp$ touch pwn
hacker@commands~touching-files:/tmp$ touch college
hacker@commands~touching-files:/tmp$ ls
bin  college  hsperfdata_root  pwn  tmp.TpSOPGOVKK
hacker@commands~touching-files:/tmp$ /challenge/run
Success! Here is your flag:
pwn.college{M7Ulhi3fkouCesg9Cb7ZneDBFcd.QXwMDO0wyM3EzNzEzW}
```
## Incorrect tangents I went on
None

## What I learned
I learned how to create files using the touch command.

## References 
None
