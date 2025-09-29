# Challenge Name
deleting characters

## My solve
**Flag:** `pwn.college{4CFj_s3Zxrwa2mL9i6JM377NSKX.0FNxEzNxwyM3EzNzEzW}`

```bash
Connected!
hacker@data~deleting-characters:~$ /challenge/run
Your character-stuffed flag:
p%w%n^%.^c%o%l^%le^g^e{4%C^%F^%j%_%s%3%Z^%x^%r%w^a^2%m^L^9^%i^%6^%J^M%3%7%7%N%S^K%X^%.%0F^%N^%x%E^z^N%x%wy%M^%3%E^%zNz^E^z%W^}%%
hacker@data~deleting-characters:~$ /challenge/run | tr -d %^
Your character-stuffed flag:
pwn.college{4CFj_s3Zxrwa2mL9i6JM377NSKX.0FNxEzNxwyM3EzNzEzW}
```
## Incorrect tangents I went on
None

## What I learned
I learned how to delete characters using tr operator.

## References 
None
