[← Back to Cybersecurity Track home](../../README.md)

# Networking Cheat Sheet

```bash
ip addr                       # your interfaces and addresses   [Windows: ipconfig /all]
ip route                      # default gateway
ping -c 4 example.com         # is a host reachable?
nslookup example.com          # DNS lookup
curl -I https://example.com   # fetch only the headers of a page
ss -tuln                      # ports listening on your own machine   [Windows: netstat -an]
```
**Ideas to know**
- **IP address:** where a device is on a network. **MAC address:** a hardware identifier.
- **DNS** turns names into addresses. **DHCP** hands out addresses.
- **TCP** is reliable and ordered, **UDP** is fast and light.
- **Ports:** web traffic usually uses 80 (HTTP) and 443 (HTTPS).

**Only run these on your own machine or public example sites. Do not scan or probe systems you do not own or have written permission to test.**

[← All resources](../README.md)
