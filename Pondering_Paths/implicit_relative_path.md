# Challenge Name
Implicit relative path

## My solve
**Flag:** `pwn.college{UP3qAH_h2YkaMRfRoWZE7CyJYKY.QXxUTN0wyM3EzNzEzW}`

```bash
Connected!
hacker@paths~implicit-relative-path:~$ cd /challenge
hacker@paths~implicit-relative-path:/challenge$ ./run
Correct!!!
./run is a relative path, invoked from the right directory!
Here is your flag:
pwn.college{UP3qAH_h2YkaMRfRoWZE7CyJYKY.QXxUTN0wyM3EzNzEzW}
```

## Incorrect tangents I went on
None

## What I learned
I learnt that to not use a naked path as it may accidently execute programs in your current directory and will show an error.

## References 
None
