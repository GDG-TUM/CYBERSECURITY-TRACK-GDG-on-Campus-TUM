[← Back to Cybersecurity Track home](../../README.md)

# Linux Cheat Sheet

```bash
pwd                    # where am I
ls -la                 # list files, including hidden ones, with permissions
cd <dir>               # change directory
cat <file>             # show a file
less <file>            # scroll through a file
grep "text" <file>     # search in a file
head -n 20 <file>      # first 20 lines
tail -f <file>         # follow a file as it grows (useful for logs)
chmod 600 <file>       # owner can read and write, no one else
whoami                 # current user
id                     # your user and groups
ps aux | head          # running processes
man <command>          # manual page
```
**SSH (only to machines you own or that the club provides)**
```bash
ssh-keygen -t ed25519   # create a key pair; keep the private key private
ssh user@lab-machine    # connect to a lab machine
```
**Pipes:** `cat file.log | grep "error" | wc -l` sends one command's output into another. Be careful with `rm`: there is no recycle bin.

[← All resources](../README.md)
