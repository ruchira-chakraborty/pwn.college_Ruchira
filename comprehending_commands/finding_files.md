# Challenge Name
Finding Files

## My solve
**Flag:** `pwn.college{cwv1t76v_f9uRKfMByxTX4ym_tf.QXyMDO0wyM3EzNzEzW}`

```bash
Connected!
hacker@commands~finding-files:~$ find -name flag
./flag
hacker@commands~finding-files:~$ cat flag
pwn.college{MEEbiSUF1mGujTdVDHDanslfi0N.QXxcTN0wyM3EzNzEzW}
hacker@commands~finding-files:~$ cd /
hacker@commands~finding-files:/$ find -name flag
./home/hacker/flag
find: ‘./tmp/tmp.TpSOPGOVKK’: Permission denied
find: ‘./etc/ssl/private’: Permission denied
./usr/local/lib/python3.8/dist-packages/pwnlib/flag
./usr/share/dictionaries-common/site-elisp/flag
find: ‘./var/cache/apt/archives/partial’: Permission denied
find: ‘./var/cache/ldconfig’: Permission denied
find: ‘./var/cache/private’: Permission denied
find: ‘./var/lib/apt/lists/partial’: Permission denied
find: ‘./var/lib/mysql-files’: Permission denied
find: ‘./var/lib/private’: Permission denied
find: ‘./var/lib/mysql’: Permission denied
find: ‘./var/lib/mysql-keyring’: Permission denied
find: ‘./var/lib/php/sessions’: Permission denied
find: ‘./var/log/private’: Permission denied
find: ‘./var/log/apache2’: Permission denied
find: ‘./var/log/mysql’: Permission denied
find: ‘./run/mysqld’: Permission denied
find: ‘./run/sudo’: Permission denied
find: ‘./root’: Permission denied
./opt/pwndbg/.venv/lib/python3.8/site-packages/pwnlib/flag


find: ‘./proc/tty/driver’: Permission denied
find: ‘./proc/1/task/1/fd’: Permission denied
find: ‘./proc/1/task/1/fdinfo’: Permission denied
find: ‘./proc/1/task/1/ns’: Permission denied
find: ‘./proc/1/fd’: Permission denied
find: ‘./proc/1/map_files’: Permission denied
find: ‘./proc/1/fdinfo’: Permission denied
find: ‘./proc/1/ns’: Permission denied
find: ‘./proc/7/task/7/fd’: Permission denied
find: ‘./proc/7/task/7/fdinfo’: Permission denied
find: ‘./proc/7/task/7/ns’: Permission denied
find: ‘./proc/7/fd’: Permission denied
find: ‘./proc/7/map_files’: Permission denied
find: ‘./proc/7/fdinfo’: Permission denied
find: ‘./proc/7/ns’: Permission denied
./nix/store/ka6xbd6z6wj5d6frl7ym4nzfc6p2wkdx-radare2-5.9.8/share/radare2/5.9.8/flag
./nix/store/f31j0igg7ms3yrj5gm3cm76bjcmdl8w5-python3.12-pwntools-4.13.1/lib/python3.12/site-packages/pwnlib/flag
./nix/store/7ns27apnvn4qj4q5c82x0z1lzixrz47p-radare2-5.9.8/share/radare2/5.9.8/flag
./nix/store/5z3sjp9r463i3siif58hq5wj5jmy5m98-python3.12-pwntools-4.13.1/lib/python3.12/site-packages/pwnlib/flag
./nix/store/n6vb30rd7kkwjj595pgm0dmsmfaqi6i5-rizin-0.7.3/share/rizin/flag
./nix/store/5n5lp1m8gilgrsriv1f2z0jdjk50ypcn-rizin-0.7.3/share/rizin/flag
./nix/store/bnlabj2vsbljhp597ir29l51nrqhm89w-rizin-0.7.4/share/rizin/flag
./nix/store/s8b49lb0pqwvw0c6kgjbxdwxcv2bp0x4-radare2-5.9.8/share/radare2/5.9.8/flag
./nix/store/8qvj9mzdq2qxgjigw4ysqgbkcx1zi80y-python3.13-pwntools-4.14.1/lib/python3.13/site-packages/pwnlib/flag
./nix/store/1hyxipvwpdpcxw90l5pq1nvd6s6jdi5m-python3.12-pwntools-4.14.1/lib/python3.12/site-packages/pwnlib/flag
./nix/store/dz2qxywk6d8hc1gkarpwbhyxb50sh2ak-pwntools-4.14.0/lib/python3.13/site-packages/pwnlib/flag
hacker@commands~finding-files:/$
hacker@commands~finding-files:/$
hacker@commands~finding-files:/$ cat /home/hacker/flag
pwn.college{MEEbiSUF1mGujTdVDHDanslfi0N.QXxcTN0wyM3EzNzEzW}
hacker@commands~finding-files:/$ cat /opt/pwndbg/.venv/lib/python3.8/site-packages/pwnlib/flag
cat: /opt/pwndbg/.venv/lib/python3.8/site-packages/pwnlib/flag: Is a directory
hacker@commands~finding-files:/$ cat /nix/store/ka6xbd6z6wj5d6frl7ym4nzfc6p2wkdx-radare2-5.9.8/share/radare2/5.9.8/flag
cat: /nix/store/ka6xbd6z6wj5d6frl7ym4nzfc6p2wkdx-radare2-5.9.8/share/radare2/5.9.8/flag: Is a directory
hacker@commands~finding-files:/$ cat /nix/store/dz2qxywk6d8hc1gkarpwbhyxb50sh2ak-pwntools-4.14.0/lib/python3.13/site-packages/pwnlib/flag
cat: /nix/store/dz2qxywk6d8hc1gkarpwbhyxb50sh2ak-pwntools-4.14.0/lib/python3.13/site-packages/pwnlib/flag: Is a directory
hacker@commands~finding-files:/$ cat /usr/local/lib/python3.8/dist-packages/pwnlib/flag
cat: /usr/local/lib/python3.8/dist-packages/pwnlib/flag: Is a directory
hacker@commands~finding-files:/$ cat /usr/share/dictionaries-common/site-elisp/flag
pwn.college{cwv1t76v_f9uRKfMByxTX4ym_tf.QXyMDO0wyM3EzNzEzW}
```
## Incorrect tangents I went on
None

## What I learned
I learned how to find files using 'find' command and that find command takes time.

## References 
None
