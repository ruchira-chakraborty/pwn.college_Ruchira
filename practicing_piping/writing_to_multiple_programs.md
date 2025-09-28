# Challenge Name
writing to multiple commands

## My solve
**Flag:** `pwn.college{0PGZhJBVx9Qjcr_Cn2gAWavHO3S.QXwgDN1wyM3EzNzEzW}`

```bash
Connected!
hacker@piping~writing-to-multiple-programs:~$ /challenge/hack | tee >(/challenge/the) >(/challenge/planet)
This secret data must directly and simultaneously make it to /challenge/the and
/challenge/planet. Don't try to copy-paste it; it changes too fast.
10433207081818313114
Congratulations, you have duplicated data into the input of two programs! Here
is your flag:
pwn.college{0PGZhJBVx9Qjcr_Cn2gAWavHO3S.QXwgDN1wyM3EzNzEzW}
```
## Incorrect tangents I went on
None

## What I learned
I learned how to use process substitution for writing to commands.

## References 
None
