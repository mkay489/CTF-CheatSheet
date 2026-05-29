# CTF-CheatSheet

![Stars](https://img.shields.io/github/stars/mkay489/ctf-cheatsheet?style=flat-square)
![Categories](https://img.shields.io/badge/categories-15-orange?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)

My personal CTF reference built from hundreds of hours on HackTheBox, TryHackMe and PicoCTF.

## What is inside

| Category | Topics |
|----------|--------|
| Recon | nmap, gobuster, ffuf, subdomain enum, SMB |
| Web | SSRF, XXE, JWT attacks, IDOR |
| SQLi | Union, Blind, Time-based, sqlmap |
| XSS | Payloads, bypass, cookie stealing |
| LFI/RFI | Path traversal, PHP wrappers |
| Shells | Bash, Python, PHP, nc, PowerShell |
| Linux PrivEsc | SUID, sudo, cron, capabilities |
| Windows PrivEsc | WinPEAS, token impersonation |
| Crypto | Hash cracking, RSA, classical ciphers |
| Stego | steghide, zsteg, binwalk, stegsolve |
| Forensics | Volatility, PCAP, disk images |
| Pwn | GDB, pwntools, format strings |
| Passwords | hashcat, john, rules, masks |
| OSINT | Google dorks, theHarvester, Shodan |
| One-liners | Quick commands for common tasks |

## Usage

Open CTF-CHEATSHEET.md directly or use any Markdown viewer.

```bash
git clone https://github.com/mkay489/ctf-cheatsheet
cd ctf-cheatsheet

# Search for a technique
grep -i "sqlmap" CTF-CHEATSHEET.md
grep -i "privesc" CTF-CHEATSHEET.md
```

## Disclaimer

For educational purposes and authorized CTF competitions and security testing only.

Writeups in /writeups/  platforms: HTB, THM, PicoCTF
