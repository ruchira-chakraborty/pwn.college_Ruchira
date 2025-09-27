# Challenge Name
Exclusionary Globbing

## My solve
**Flag:** `pwn.college{0MHB-QzDQDeiGyREX5FovcwztSF.QX2IDO0wyM3EzNzEzW}`

```bash
Connected!
hacker@globbing~exclusionary-globbing:~$ cd /challenge/files
hacker@globbing~exclusionary-globbing:/challenge/files$ /challenge/run [^pwn]
Your expansion did not expand to the requested files (amazing beautiful
challenging delightful educational fantastic great happy incredible jovial kind
laughing magical optimistic queenly radiant splendid thrilling uplifting
victorious xenial youthful zesty).
Instead, it expanded to:
[^pwn]
hacker@globbing~exclusionary-globbing:/challenge/files$ /challenge/run [^pwn]*
You got it! Here is your flag!
pwn.college{0MHB-QzDQDeiGyREX5FovcwztSF.QX2IDO0wyM3EzNzEzW}
```
## Incorrect tangents I went on
None

## What I learned
I learned how to filter files in glob command.

## References 
None
