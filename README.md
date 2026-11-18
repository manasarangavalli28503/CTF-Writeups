# Offensive Security Write-ups

Penetration testing and CTF write-ups covering Active Directory attacks, web exploitation, CVE weaponisation and Linux/Windows privilege escalation.

**Live site:** https://manasarangavalli28503.github.io/CTF-Writeups/

## Write-ups

| Machine | Platform | OS | Difficulty | Key techniques | PDF |
|---|---|---|---|---|---|
| Intentions | Hack The Box | Linux | Hard | Second-order SQLi, hash login abuse, Imagick MSL write, git history creds | [PDF](writeups/intentions.pdf) |
| Forest | Hack The Box | Windows | Easy | RPC enum, AS-REP roasting, BloodHound, Exchange ACL → DCSync | [PDF](writeups/forest.pdf) |
| Sauna | Hack The Box | Windows | Easy | username-anarchy, AS-REP roasting, Evil-WinRM, DCSync, PtH | [PDF](writeups/sauna.pdf) |
| Active | Hack The Box | Windows | Easy | Anonymous SMB, GPP cpassword, Kerberoasting | [PDF](writeups/active.pdf) |
| Outbound | Hack The Box | Linux | Easy | Roundcube CVE-2025-49113, mailbox credential harvesting | [PDF](writeups/outbound.pdf) |
| Broker | Hack The Box | Linux | Easy | ActiveMQ CVE-2023-46604, sudo nginx misconfig | [PDF](writeups/broker.pdf) |
| Sau | Hack The Box | Linux | Easy | Request-Baskets SSRF, Maltrail RCE, systemctl pager escape | [PDF](writeups/sau.pdf) |
| Busqueda | Hack The Box | Linux | Easy | Searchor command injection, .git creds, relative path hijack | [PDF](writeups/busqueda.pdf) |
| Help | Hack The Box | Linux | Easy | HelpDeskZ upload bypass, kernel exploit | [PDF](writeups/help.pdf) |
| Smol | TryHackMe | Linux | Medium | WordPress plugin LFI, backdoor RCE, hash & zip cracking | [PDF](writeups/smol.pdf) |
| Wonderland | TryHackMe | Linux | Medium | Python library hijack, PATH hijack, perl capabilities | [PDF](writeups/wonderland.pdf) |
| Cheese CTF | TryHackMe | Linux | Easy | LFI, PHP filter chain RCE, systemd timer, SUID xxd | [PDF](writeups/cheese-ctf.pdf) |
| Lookup *(pentest report)* | TryHackMe | Linux | Easy | wfuzz, Hydra, elFinder CVE-2019-9194, SUID PATH hijack | [PDF](writeups/lookup-pentest-report.pdf) |
| Pyrat | TryHackMe | Linux | Easy | Python RCE service, custom socket brute-forcer | [PDF](writeups/pyrat.pdf) |
| SQLi, XSS & CSRF Labs | Web Security | Web | Medium | XML-encoded SQLi WAF bypass, stored XSS → CSRF | [PDF](writeups/portswigger-sqli-xss-csrf.pdf) |

## Tooling

Nmap · Burp Suite · Caido · sqlmap · gobuster · dirsearch · wfuzz · Hydra · Impacket · BloodHound · Evil-WinRM · Hashcat · John the Ripper · linpeas

---

*All write-ups cover retired or lab machines and are published for educational purposes only.*
