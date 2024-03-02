## Most Common Wireshark Filters

1. **IP Address Filter:**
   - Syntax: `ip.addr == <IP Address>`
   - Example: `ip.addr == 192.168.1.100`
   - Description: Filter packets with a specific source or destination IP address.

2. **Protocol Filter:**
   - Syntax: `ip.proto == <Protocol Number>`
   - Example: `ip.proto == 6` (TCP) or `ip.proto == 17` (UDP)
   - Description: Filter packets based on the protocol they use.

3. **Port Filter:**
   - Syntax: `tcp.port == <Port Number>` or `udp.port == <Port Number>`
   - Example: `tcp.port == 80` (HTTP) or `udp.port == 53` (DNS)
   - Description: Filter packets based on the source or destination port number.

4. **Display Filter:**
   - Syntax: `display filter string`
   - Example: `http.request.method == "GET"`
   - Description: Specify display filters using Wireshark's display filter syntax.

5. **MAC Address Filter:**
   - Syntax: `eth.addr == <MAC Address>`
   - Example: `eth.addr == 00:11:22:33:44:55`
   - Description: Filter packets based on the source or destination MAC address.

6. **DNS Filter:**
   - Syntax: `dns`
   - Example: `dns.qry.name == "example.com"`
   - Description: Filter DNS traffic and queries.

9. **HTTP Filter:**
   - Syntax: `http`
   - Example: `http.request.method == "POST"`
   - Description: Filter HTTP traffic and requests.

10. **ICMP Filter:**
    - Syntax: `icmp`
    - Example: `icmp.type == 8`
    - Description: Filter ICMP traffic and packets.

11. **ARP Filter:**
    - Syntax: `arp`
    - Example: `arp.opcode == 1`
    - Description: Filter ARP (Address Resolution Protocol) traffic.

12. **SSL/TLS Filter:**
    - Syntax: `ssl` or `tls`
    - Example: `ssl.handshake.type == 1`
    - Description: Filter SSL/TLS encrypted traffic.

13. **IPv6 Filter:**
    - Syntax: `ipv6`
    - Example: `ipv6.dst == 2001:db8::1`
    - Description: Filter IPv6 traffic and packets.

14. **UDP Length Filter:**
    - Syntax: `udp.length == <Length>`
    - Example: `udp.length == 128`
    - Description: Filter UDP packets based on their length.

15. **TCP Length Filter:**
    - Syntax: `tcp.len == <Length>`
    - Example: `tcp.len > 100`
    - Description: Filter TCP packets based on their length.

16. **Time Range Filter:**
    - Syntax: `frame.time >= "<Start Time>" && frame.time <= "<End Time>"`
    - Example: `frame.time >= "2022-01-01 12:00:00" && frame.time <= "2022-01-01 13:00:00"`
    - Description: Filter packets within a specified time range.

17. **Packet Length Filter:**
    - Syntax: `frame.len == <Length>`
    - Example: `frame.len < 500`
    - Description: Filter packets based on their length.

18. **Packet Direction Filter:**
    - Syntax: `ip.src == <Source IP> && ip.dst == <Destination IP>`
    - Example: `ip.src == 192.168.1.100 && ip.dst == 192.168.1.200`
    - Description: Filter packets based on their direction (source to destination or vice versa).

19. **Frame Type Filter:**
    - Syntax: `frame.type == <Type>`
    - Example: `frame.type == 1`
    - Description: Filter packets based on their frame type.

20. **Ethernet Type Filter:**
    - Syntax: `eth.type == <Type>`
    - Example: `eth.type == 0x0800`
    - Description: Filter packets based on their Ethernet type.
