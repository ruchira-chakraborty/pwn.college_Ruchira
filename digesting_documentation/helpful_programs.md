# Challenge Name
Helpful programs

## My solve
**Flag:** `pwn.college{48P-TH9f3z_HlHmLWB1fVJPuyxw.QX3IDO0wyM3EzNzEzW}`

```bash
Connected!
hacker@man~helpful-programs:~$ /challenge/challenge --help
usage: a challenge to make you ask for help [-h] [--fortune] [-v] [-g GIVE_THE_FLAG] [-p]

optional arguments:
  -h, --help            show this help message and exit
  --fortune             read your fortune
  -v, --version         get the version number
  -g GIVE_THE_FLAG, --give-the-flag GIVE_THE_FLAG
                        get the flag, if given the correct value
  -p, --print-value     print the value that will cause the -g option to give you the flag
hacker@man~helpful-programs:~$ /challenge/challenge -p
The secret value is: 489
hacker@man~helpful-programs:~$ /challenge/challenge -g 489
Correct usage! Your flag: pwn.college{48P-TH9f3z_HlHmLWB1fVJPuyxw.QX3IDO0wyM3EzNzEzW}
```
## Incorrect tangents I went on
None

## What I learned
I learned how  to use the help command for cases when programs do not have man page.

## References 
None
