[← Back to Cybersecurity Track home](../README.md)


# Wireshark and Log Investigation Lab

**Stage:** Practice (Practitioner) · **When:** Week 9 · **Time:** 90 minutes

**Goal:** Read packet captures and logs like a defender, and write a short investigation.

> [!IMPORTANT]
> Practise only on systems built for it. See the [rules of engagement](../ETHICS-AND-RULES.md).

## What you need
Wireshark installed, and the sample capture and log file prepared by the team.

## What you will be able to do
- Open a capture and use basic display filters
- Follow a conversation between two hosts
- Read log lines and spot unusual activity
- Build a short timeline and summary

## Steps
**Step 1: Open the sample capture** provided by the team (fictional data) and try some display filters:
```
dns
http
tcp.port == 443
ip.addr == 192.0.2.10
```
**Step 2: Follow a conversation**: right-click a packet, choose *Follow*, and note what was exchanged.

**Step 3: Read the sample log** (made-up data, documentation addresses)
```
Oct 16 09:12:01 server sshd[311]: Failed password for invalid user admin from 203.0.113.5 port 52244 ssh2
Oct 16 09:12:03 server sshd[311]: Failed password for invalid user admin from 203.0.113.5 port 52246 ssh2
Oct 16 09:12:05 server sshd[311]: Failed password for invalid user test from 203.0.113.5 port 52250 ssh2
Oct 16 09:40:22 server sshd[402]: Accepted publickey for mark from 198.51.100.7 port 40112 ssh2
```
Ask: what repeats? What is normal? What would you alert on?

**Step 4:** Write a timeline and a three-sentence summary.

## ✅ Lab checkpoints
Log these with the Labs/CTF Coordinator. Labs completed, not attendance, count towards your badge.
- [ ] Three display filters used
- [ ] One conversation followed and explained
- [ ] Suspicious log lines identified
- [ ] Timeline and summary written

## Safety
Use the **provided sample files**. Only capture traffic on **your own machine on your own network**, never on shared or public networks you do not control.

[← All labs](README.md)
