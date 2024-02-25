# tcpdump most common options

## read pcap

`tcpdump -D`

*	show all available interface.

`tcpdump -i <interface name>`

*	Specifies the interface to capture packets from.

`tcpdump -n`

*	Prevents TCPdump from performing reverse DNS lookups on IP addresses.

`tcpdump -t`

*	Don't show timestamp

`tcpdump -c`

*	Specifies the number of packets to capture before stopping.

`tcpdump -w`

*	Writes the captured packets to a file rather than displaying them on the terminal.

`tcpdump -A`

*	Prints packet data in ASCII format for easier readability.

`tcpdump -x`

*	This option displays packet data in hexadecimal format without any ASCII representation.

`tcpdump -X`

*	This option displays packet data in ASCII format alongside its hexadecimal representation.

`tcpdump -xx`

*	Similar to -x, it displays packet data in hexadecimal format, but also includes the ethernet header at the beginning of each line.

`tcpdump -XX`

*	Similar to -X, but it also includes the ethernet header at the beginning of each line.

`tcpdump -v`

*	Increases verbosity, providing more detailed information about captured packets.

`tcpdump -r <file name>`

*	Reads packets from a saved capture file for analysis.

