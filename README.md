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

## Passwords Tools

## Ansible

```bash
ansible2john <file>
```

## websites

- [OWASP](https://owasp.org)

- [HackTricks](https://book.hacktricks.xyz)

## tools

- [Burp Suite](https://portswigger.net/burp/communitydownload): Web penetration testing

- [wappalyzer](https://www.wappalyzer.com/apps/): web site analysis
