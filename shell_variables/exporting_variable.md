# Challenge Name
exporting variables

## My solve
**Flag:** `pwn.college{ExGVTOSt34IZEW7ho1XTdzHxfD7.QXyYTN0wyM3EzNzEzW}`

```bash
Connected!
hacker@variables~exporting-variables:~$ export PWN=COLLEGE
You've set the PWN variable to the proper value!
hacker@variables~exporting-variables:~$ COLLEGE=PWN
You've set the PWN variable to the proper value!
You've set the COLLEGE variable to the proper value!
hacker@variables~exporting-variables:~$ /challenge/run $PWN
CORRECT!
You have exported PWN=COLLEGE and set, but not exported, COLLEGE=PWN. Great
job! Here is your flag:
pwn.college{ExGVTOSt34IZEW7ho1XTdzHxfD7.QXyYTN0wyM3EzNzEzW}
You've set the PWN variable to the proper value!
You've set the COLLEGE variable to the proper value!
```
## Incorrect tangents I went on
None

## What I learned
I learned how to store the values assigned to a variable for future use using export command.

## References 
None
