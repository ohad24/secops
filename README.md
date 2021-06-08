# SecOps

## Nmap

https://github.com/nmap/nmap

```bash
IP=8.8.8.8

nmap $IP

# -sV: Probe open ports to determine service/version info
# -sC: equivalent to --script=default
# -p <port ranges>: Only scan specified ports
#     Ex: -p22; -p1-65535; -p U:53,111,137,T:21-25,80,139,8080,S:9
nmap $IP -sC -sV
```



https://github.com/Gallopsled/pwntools
https://github.com/calebstewart/pwncat
https://github.com/swisskyrepo/PayloadsAllTheThings (reverse shell)
https://github.com/rapid7/metasploit-framework
https://github.com/carlospolop/privilege-escalation-awesome-scripts-suite
https://gtfobins.github.io/