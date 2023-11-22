# h4ck3r

## Scan Tools

### nmap

Options:

- `-sV`: Service Version Detection

- `-sC`: Script Scan

- `-sS`: TCP SYN Scan

```bash
# common ports:
nmap <options> <ip>

# all ports:
nmap -p- <options> <ip>
```

### massscan

```bash
masscan -p1-65535,U:1-65535 <ip> --rate=1000 -e tun0
```

### gobuster

```bash
gobuster dir -u <http://ip> -w /usr/share/dirbuster/wordlists/<directory-list.txt> -x <.ext>
```

### dirsearch

```bash
dirsearch -u <hostname>
```

## Exploit Tools

### Metasploit

```bash
msfconsole
```

## Passwords Tools

### hashcat

```bash
hashcat -a 0 -m 3200 hash.txt /usr/share/wordlists/rockyou.txt.gz
```

## Scripts

- [linpeas.sh](https://github.com/carlospolop/PEASS-ng/tree/master/linPEAS): Linux Privilege Escalation Awesome Script

- [FullPowers](https://github.com/itm4n/FullPowers): Windows - Recover the default privilege set of a LOCAL/NETWORK SERVICE account

- [GodPotato](https://github.com/BeichenDream/GodPotato): Windows - Potato privilege escalation

- [bloodyAD](https://github.com/CravateRouge/bloodyAD): Windows - Active Directory Privilege Escalation Framework

## Websites

- [OWASP](https://owasp.org)

- [HackTricks](https://book.hacktricks.xyz)

- [Crowd Strike](https://www.crowdstrike.com/blog/)

## Tools

- [Burp Suite](https://portswigger.net/burp/communitydownload): Web penetration testing

- [wappalyzer](https://www.wappalyzer.com/apps/): Web site analysis

- [Hex Rays IDA](https://hex-rays.com/ida-free): Reverse engineer tool
