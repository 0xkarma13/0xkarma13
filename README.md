<p align="center">
  <img src="https://raw.githubusercontent.com/0xkarma13/0xkarma13/main/banner.svg" alt="KARMA" width="100%" />
</p>

<p align="center">
  <code>0xkarma13</code> · penetration tester in training · CTF player · <b>Security+ certified</b>
</p>

```console
karma@0x13:~$ cat about.txt

I play CTFs because they sharpen how I think, but they are practice, not the goal.
What I actually want is to find real problems in real systems, and help fix them.
So I break things in labs, hunt bugs, and write down everything I learn.
```

```diff
- CTF is the gym.
+ the real world is the match.
```

---

## `$ sudo -l`  (what I can do)

```console
offense     burp-suite  nmap  metasploit  sqlmap  hydra  john  gobuster  dotdotpwn
forensics   wireshark  tcpdump  volatility  binwalk  exiftool  steghide  cyberchef
web         sqli  xss  idor  broken-access-control  lfi  path-traversal  file-upload-rce
crypto      aes  rsa  xor  known-plaintext  hashing  pgp
network     tcp-ip  dns  dhcp  nat  vpn  tls
systems     linux (kali, ubuntu)  windows
code        python  bash  c (learning)
```

---

## `$ cat case_files.log`  (things I've cracked and written up)

| Case | Platform | Category | What it took |
|------|----------|----------|--------------|
| Broken Access Control | TryHackMe | Web | IDOR and privilege escalation by flipping an `isadmin` param in Burp |
| Lo-Fi | TryHackMe | Web | Path traversal / LFI through a `?page=` parameter |
| Dreaming | TryHackMe | Web | DNS recon, fuzzing, Pluck CMS CVE-2020-29607 `.phar` upload to RCE |
| W1seGuy | TryHackMe | Crypto | XOR known-plaintext attack |
| Ninja Skills | TryHackMe | Linux | Finding files by attributes across the system |
| Carnage | TryHackMe | DFIR | Malspam pcap in Wireshark: Squirrelwaffle, Qakbot, Cobalt Strike |
| midnight_beacon | unlim.ir | Forensics | DNS beacon chunks in a pcap, base64, XOR |
| MacroHard WeakEdge | picoCTF | Forensics | `.pptm` unpacked with binwalk, hidden folder, base64 |
| Trivial Flag Transfer Protocol | picoCTF | Forensics | TFTP pcap, ROT13 hints, steghide |
| Wireshark doo dooo | picoCTF | Forensics | Follow HTTP stream, ROT13 in CyberChef |
| Sleuthkit Apprentice | picoCTF | Forensics | Disk image analysis with Sleuthkit |
| shark on wire 1 / 2 | picoCTF | Forensics | Fake flag in UDP stream, real one hidden one char per packet |
| wireshark-tooo-tooo | CTF | Forensics | Decoy flags in HTTP, real flag as base64 pieces in DNS |
| WebNet0 / WebNet1 | CTF | Forensics | TLS key in Wireshark, Export Objects, exiftool |
| MemLabs Lab 0 | MemLabs | Memory forensics | Volatility `windows.info` and first steps |

Full write-ups, no flags spoiled, live in [pentest-writeups](https://github.com/0xkarma13/pentest-writeups) and [ctf-writeups](https://github.com/0xkarma13/ctf-writeups).

---

## `$ cat roadmap.mmd`

```mermaid
%%{init: {'theme':'base','themeVariables':{'primaryColor':'#0a0a0a','primaryTextColor':'#ffffff','primaryBorderColor':'#ff1f1f','lineColor':'#ff1f1f','fontFamily':'monospace'}}}%%
flowchart LR
    A[Networking basics] --> B[Security+]
    B --> C[CTFs and forensics]
    C --> D[Bug bounty]
    D --> E[eJPT]
    E --> F[OSCP]
    style B fill:#ff1f1f,stroke:#ffffff,color:#ffffff
    style C fill:#ff1f1f,stroke:#ffffff,color:#ffffff
```

Red means done or in progress.

---

## `$ ls work/`

```console
pentest-writeups/                lab reports, TryHackMe write-ups
ctf-writeups/                    forensics, crypto, web challenges
cybersecurity-notes/             linux, networking, crypto notes
cybersecurity-knowledge-base/    research and resources
```

[pentest-writeups](https://github.com/0xkarma13/pentest-writeups) ·
[ctf-writeups](https://github.com/0xkarma13/ctf-writeups) ·
[cybersecurity-notes](https://github.com/0xkarma13/cybersecurity-notes) ·
[cybersecurity-knowledge-base](https://github.com/0xkarma13/cybersecurity-knowledge-base)

---

## `$ cat rules.txt`

```console
1. Understand it before you exploit it.
2. If I can't explain it, I haven't solved it yet.
3. Every solve gets a write-up, written in my own words.
4. Never publish the flag, publish the thinking.
5. Break things only where I'm allowed to.
```

---

## `$ cat contact`

```console
linkedin    in/createrkarma11
hackerone   <your-username>
tryhackme   <your-username>
email       CreaterKarma9900@gmail.com
```

[LinkedIn](https://linkedin.com/in/createrkarma11) · [Email](mailto:CreaterKarma9900@gmail.com)

```console
karma@0x13:~$ _
```
