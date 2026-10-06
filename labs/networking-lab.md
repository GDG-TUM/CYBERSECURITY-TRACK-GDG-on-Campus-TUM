[← Back to Cybersecurity Track home](../README.md)


# Networking Lab

**Stage:** Foundations (Learner) · **When:** Weeks 5–8 · **Time:** 60–90 minutes

**Goal:** Understand how devices find each other and exchange data.

> [!IMPORTANT]
> Practise only on systems built for it. See the [rules of engagement](../ETHICS-AND-RULES.md).

## What you need
A terminal and a browser. Windows equivalents are in brackets.

## What you will be able to do
- Explain the difference between an IP address and a MAC address
- Describe what DNS and DHCP do
- Tell TCP and UDP apart
- Explain ports and HTTP versus HTTPS

## Steps
**Step 1: Find your own network details**
```bash
ip addr            # your interfaces and addresses   [Windows: ipconfig /all]
ip route           # your default gateway
```
**Step 2: Follow a name to an address**
```bash
nslookup example.com
```
**Step 3: See what is listening on your own machine**
```bash
ss -tuln           # [Windows: netstat -an]
```
**Step 4: Compare HTTP and HTTPS headers on a public example site**
```bash
curl -I https://example.com
```
**Step 5:** Draw a diagram of what happens when you open a website: DHCP, DNS, TCP connection, TLS, HTTP request.

## ✅ Lab checkpoints
Log these with the Labs/CTF Coordinator. Labs completed, not attendance, count towards your badge.
- [ ] Network details recorded for your own device
- [ ] DNS lookup explained in your own words
- [ ] Diagram of a web request
- [ ] Explanation of a port, in one sentence

## Safety
Run commands against **your own machine and public example sites only**. Never scan or probe systems you do not own.

[← All labs](README.md)
