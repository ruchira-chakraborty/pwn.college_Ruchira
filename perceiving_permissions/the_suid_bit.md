# Challenge Name
the SUID bit

## My solve
**Flag:** `pwn.college{ofjlYNamGp3ya7Ph3kIqMZNwD8X.QXzEjN0wyM3EzNzEzW}`

```bash
Connected!
hacker@permissions~the-suid-bit:~$ chmod u+s /challenge/getroot
hacker@permissions~the-suid-bit:~$ /challenge/getroot
SUCCESS! You have set the suid bit on this program, and it is running as root!
Here is your shell...
root@permissions~the-suid-bit:~# cat /flag
pwn.college{ofjlYNamGp3ya7Ph3kIqMZNwD8X.QXzEjN0wyM3EzNzEzW}
```
## Incorrect tangents I went on
None

## What I learned
I learned how to give SUID permissions to a file.

## References 
None
