# Challenge Name
extracting specific sections of text

## My solve
**Flag:** `pwn.college{obvz6AjKmfRvA-t8q6yXytsYsyY.01NxEzNxwyM3EzNzEzW}`

```bash
Connected!
hacker@data~extracting-specific-sections-of-text:~$ /challenge/run
17735 p
18851 w
7561 n
6199 .
20125 c
25134 o
17317 l
6294 l
24920 e
3072 g
3566 e
9988 {
10314 o
8486 b
20775 v
31500 z
26133 6
30928 A
12346 j
21687 K
27118 m
11364 f
3208 R
15116 v
13734 A
24195 -
3830 t
25325 8
27184 q
9863 6
7923 y
1222 X
6692 y
25166 t
10303 s
25638 Y
9094 s
19774 y
20178 Y
28602 .
12202 0
29798 1
5530 N
20023 x
4450 E
19057 z
22816 N
24630 x
2461 w
22052 y
30838 M
16142 3
12773 E
20814 z
31047 N
14827 z
32385 E
27614 z
24829 W
8022 }
hacker@data~extracting-specific-sections-of-text:~$ /challenge/run | cut -d " " -f 2 | tr -d "\n"
pwn.college{obvz6AjKmfRvA-t8q6yXytsYsyY.01NxEzNxwyM3EzNzEzW}
```
## Incorrect tangents I went on
None

## What I learned
I learned how to extract specific texts from a file using cut operator.

## References 
None
