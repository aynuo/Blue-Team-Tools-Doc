# tcpdump filters 

## show use filters

`tcpdump 'your filter'`

## filters 

1. `host 192.168.1.100`: Display all packets sent to or received from the IP address 192.168.1.100.

2. `net 192.168.0.0/16`: Display all packets sent to or received from the network with the IP address 192.168.0.0/16.

3. `port 80`: Display all packets sent to or received from port 80.

4. `src 192.168.1.100`: Display all packets sent from the IP address 192.168.1.100.

5. `dst 192.168.1.100`: Display all packets sent to the IP address 192.168.1.100.

6. `tcp`: Display all TCP packets.

7. `udp`: Display all UDP packets.

8. `icmp`: Display all ICMP packets.

9. `ether host 00:11:22:33:44:55`: Display all packets sent from or to the MAC address 00:11:22:33:44:55.

10. `gateway 192.168.1.1`: Display all packets passing through the gateway 192.168.1.1.

11. `src or dst port 22`: Display all packets sent to or received from port 22.

12. `vlan 100`: Display all packets belonging to VLAN 100.

13. `icmp[icmptype] 8`: Display all ICMP packets with type 8 (Echo Request).

14. `ip[8:1] > 64`: Display all packets with TTL greater than 64.

15. `src or dst net 192.168.0.0/24`: Display all packets sent to or received from the network with the IP address 192.168.0.0/24.

16. `tcp flags SYN`: Display all TCP packets with the SYN flag.

17. `ip protochain 6`: Display all packets using the TCP protocol.

18. `src or dst portrange 1024-65535`: Display all packets sent to or received from the port range 1024 to 65535.

19. `src or dst netmask 255.255.255.0`: Display all packets sent to or received from a subnet with the network mask 255.255.255.0.

20. `ip broadcast`: Display all packets sent to the IP broadcast address.
