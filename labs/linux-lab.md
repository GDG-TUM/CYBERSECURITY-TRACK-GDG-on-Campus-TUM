[← Back to Cybersecurity Track home](../README.md)


# Linux Lab

**Stage:** Foundations (Learner) · **When:** Weeks 5–8 · **Time:** 60–90 minutes

**Goal:** Become comfortable in the terminal, including permissions and SSH.

> [!IMPORTANT]
> Practise only on systems built for it. See the [rules of engagement](../ETHICS-AND-RULES.md).

## What you need
A Linux terminal (Linux, WSL, or a VM).

## What you will be able to do
- Navigate and manage files from the command line
- Read and change file permissions
- Explain what SSH is and why keys beat passwords
- Find your way around with help and search

## Steps
**Step 1: Move around**
```bash
pwd; ls -la; cd ~; mkdir lab; cd lab; touch notes.txt
```
**Step 2: Permissions**
```bash
ls -l notes.txt
chmod 600 notes.txt      # only you can read and write
ls -l notes.txt
```
**Step 3: Users and processes**
```bash
whoami; id; ps aux | head
```
**Step 4: SSH basics (only to a lab VM you own or one the club provides)**
```bash
ssh-keygen -t ed25519    # create a key pair (keep the private key private)
ssh user@lab-machine     # connect to a lab machine
```
**Step 5:** Use `man` and `grep` to answer a question without searching online.

## ✅ Lab checkpoints
Log these with the Labs/CTF Coordinator. Labs completed, not attendance, count towards your badge.
- [ ] Files created and permissions changed
- [ ] Explanation of the permission string `-rw-------`
- [ ] Key pair created, with the private key kept private
- [ ] One command learned from `man`

## Safety
SSH **only to machines you own or that the club provides for the lab**. Never connect to other people's servers.

[← All labs](README.md)
