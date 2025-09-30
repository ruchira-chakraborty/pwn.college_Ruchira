# Challenge Name
cracking passwords

## My solve
**Flag:** `pwn.college{QusndjNfwjRDsIXvi8pX4MYu_XD.QX3UDN1wyM3EzNzEzW}`

```bash
Connected!
hacker@users~cracking-passwords:~$ john /challenge/shadow-leak
Loaded 1 password hash (crypt, generic crypt(3) [?/64])
Press 'q' or Ctrl-C to abort, almost any other key for status
aardvark         (zardus)
1g 0:00:00:20 100% 2/3 0.04899g/s 285.3p/s 285.3c/s 285.3C/s Johnson..buzz
Use the "--show" option to display all of the cracked passwords reliably
Session completed
hacker@users~cracking-passwords:~$ su zardus
Password:
zardus@users~cracking-passwords:/home/hacker$ /challenge/run
Congratulations, you have become Zardus! Here is your flag:
pwn.college{QusndjNfwjRDsIXvi8pX4MYu_XD.QX3UDN1wyM3EzNzEzW}
```
## Incorrect tangents I went on
None

## What I learned
I learned how to crack passwords.

## References 
None
