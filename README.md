# ft_inquisitor

ARP spoofer based on python. With academical purpose, this project aims to perform full-duplex spoofing in a given LAN.

- The LAN is formed by one FTP client and one FTP server (or gateway). The goal of this spoofer is
to sniff the traffic between the ftp client and the ftp server.
- Server, Client and spoofer are deployed on Docker and the network environment is configured usingdocker networking and version IPV4.
- The ARP spoofing is stoped pressing CTRL+C.
