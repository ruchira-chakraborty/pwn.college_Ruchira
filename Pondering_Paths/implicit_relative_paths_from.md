# Challenge Name
Implicit relative paths, from /

## My solve
**Flag:** `pwn.college{kjEUcRc-GKRzzMaaYNPLtqEMK0j.QX5QTN0wyM3EzNzEzW}`

```bash
Connected!
hacker@paths~implicit-relative-paths-from-:~$ cd /c
bash: cd: /c: No such file or directory
hacker@paths~implicit-relative-paths-from-:~$ cd /
hacker@paths~implicit-relative-paths-from-:/$ c
bash: c: command not found
hacker@paths~implicit-relative-paths-from-:/$ challenge/run
Correct!!!
challenge/run is a relative path, invoked from the right directory!
Here is your flag:
pwn.college{kjEUcRc-GKRzzMaaYNPLtqEMK0j.QX5QTN0wyM3EzNzEzW}
```

## Incorrect tangents I went on
The hint confused me and i thought c being a relative path should be another directory.

## What I learned
I learned about relative paths.

## References 
None
