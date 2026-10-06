[← Back to Cybersecurity Track home](../../README.md)

# Wireshark Cheat Sheet

Use Wireshark on the **sample capture files from the team** or on **your own machine on your own network** only.

**Display filters (type into the filter bar)**
```
dns                     # DNS traffic
http                    # unencrypted web traffic
tcp.port == 443         # HTTPS traffic
ip.addr == 192.0.2.10   # traffic to or from one address
tcp.flags.syn == 1      # connection start packets
```
**Useful actions**
- Right-click a packet, then **Follow**, to read a whole conversation
- **Statistics → Conversations** shows who talked to whom
- **File → Export** to save what you need for a write-up

**Questions to ask**
- Who is talking to whom, and about what?
- What looks normal? What looks unusual?
- What would you want an alert on?

[← All resources](../README.md)
