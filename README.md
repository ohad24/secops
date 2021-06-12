# SecOps

## General Tools
[Pwntools](https://github.com/Gallopsled/pwntools) - Pwntools is a CTF framework and exploit development library.  
[pwncat](https://github.com/calebstewart/pwncat) - pwncat is a post-exploitation platform.  
[Payloads All The Things](https://github.com/swisskyrepo/PayloadsAllTheThings) (reverse shell) - A list of useful payloads and bypasses for Web Application Security.  
[Metasploit](https://github.com/rapid7/metasploit-framework) - The world’s most used penetration testing framework.  
[PEASS (linPEAS)](https://github.com/carlospolop/privilege-escalation-awesome-scripts-suite) - privilege escalation tools.  
[GTFOBins](https://gtfobins.github.io/) - GTFOBins is a curated list of Unix binaries that can be used to bypass local security restrictions in misconfigured systems.  
[CyberChef](https://gchq.github.io/CyberChef/) - A web app for encryption, encoding, compression and data analysis. [GitHub repo](https://github.com/gchq/CyberChef)  
[Gobuster](https://github.com/OJ/gobuster) - Gobuster is a tool used to brute-force URIs.  
[DirBuster](https://gitlab.com/kalilinux/packages/dirbuster) - Brute force directories and files names on web/application servers.  
[Shodan](https://www.shodan.io/) - Search Engine for the Internet of Things.  

## CLI Examples
### Nmap

https://github.com/nmap/nmap

```bash
IP=1.2.3.4

nmap $IP

# -sV: Probe open ports to determine service/version info
# -sC: equivalent to --script=default
# -p <port ranges>: Only scan specified ports
#     Ex: -p22; -p1-65535; -p U:53,111,137,T:21-25,80,139,8080,S:9
nmap $IP -sC -sV
```

