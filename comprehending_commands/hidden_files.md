# Challenge Name
Hidden files

## My solve
**Flag:** `pwn.college{AExD35pLZ8o-eTCc8KPs4O8hWn4.QXwUDO0wyM3EzNzEzW}`

```bash
Connected!
hacker@commands~hidden-files:~$ cd /
hacker@commands~hidden-files:/$ ls
bin   challenge  etc   lib    lib64   media  nix  proc  run   srv  tmp  var
boot  dev        home  lib32  libx32  mnt    opt  root  sbin  sys  usr
hacker@commands~hidden-files:/$ ls -a
.   .dockerenv             bin   challenge  etc   lib    lib64   media  nix  proc  run   srv  tmp  var
..  .flag-114311110211814  boot  dev        home  lib32  libx32  mnt    opt  root  sbin  sys  usr
hacker@commands~hidden-files:/$ cat  .flag-114311110211814
pwn.college{AExD35pLZ8o-eTCc8KPs4O8hWn4.QXwUDO0wyM3EzNzEzW}
```
## Incorrect tangents I went on
None

## What I learned
I learned how to list down hidden files.

## References 
None
