<img width="100%" height="180" alt="image" src="https://github.com/user-attachments/assets/5c5f2975-9492-40ad-8de3-669e0fce09bd" />


**cli_fer** is a pure terminal cheat-sheet tool that instantly shows you the most essential syntax, common flags, and ready-to-copy-paste examples for over **120+ security and system tools** across **20+ categories**.

No GUI. No bloat. Just `python cli_fer <tool>` and you're done.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.6%2B-blue.svg)](https://www.python.org/)
[![Cat Friendly](https://img.shields.io/badge/Cat-Friendly-ff69b4.svg)]()

####  Quick Start

```bash
# Clone or download the script
git clone <your-repo-url>
cd cli_fer

# Browse all tools (categorized)
python cli_fer

# Look up a specific tool
python cli_fer nmap
python cli_fer hashcat
python cli_fer sqlmap
python cli_fer steghide
```


#####  Features

| Feature | Description |
|---------|-------------|
|  **Instant Lookup** | `python cli_fer <tool>` shows flags, descriptions, and examples |
|  **Category Browsing** | Run without arguments to see all tools grouped by category |
|  **Fuzzy Matching** | Typo? `namp` → suggests `nmap` automatically |
|  **Copy-Paste Ready** | Every entry includes real-world example commands |
|  **Cute Cat Mascot** | Because hackers need joy too |



#####  Categories Covered

| Category | Tools Included |
|----------|---------------|
| **Linux Fundamentals** | `ls`, `cd`, `find`, `grep`, `ps`, `kill`, `chmod`, `chown`, `systemctl`, `journalctl`, `mount`, `fdisk`, `df`, `du`, `env` |
| **Text Processing** | `cat`, `head`, `tail`, `grep`, `awk`, `sed`, `cut`, `sort`, `uniq`, `tr`, `wc`, `diff` |
| **Shell & Scripting** | `bash`, `export`, `source`, `xargs`, `tee`, loops, conditionals |
| **Archives & Compression** | `tar`, `gzip`, `zip`, `7z`, `binwalk`, `foremost`, `scalpel` |
| **Networking Fundamentals** | `ip`, `ss`, `dig`, `curl`, `wget`, `ssh`, `socat`, `nc`, `tcpdump` |
| **Web Enumeration** | `gobuster`, `ffuf`, `wfuzz`, `feroxbuster`, `nikto`, `whatweb`, `sqlmap`, `subfinder`, `amass` |
| **Cryptography** | `base64`, `xxd`, `openssl`, `gpg`, `hash-identifier`, `RsaCtfTool`, `cewl`, `john` |
| **Password Attacks** | `hashcat`, `john`, `hydra`, `medusa`, `crunch` |
| **Reverse Engineering** | `strings`, `objdump`, `radare2`, `gdb`, `readelf`, `strace`, `ltrace`, `binwalk`, `upx` |
| **Binary Exploitation** | `checksec`, `ROPgadget`, `Ropper`, `one_gadget`, `pwntools`, `gdb-pwndbg` |
| **Forensics** | `dd`, `dcfldd`, `mmls`, `fls`, `icat`, `volatility3`, `strings`, `exiftool`, `testdisk`, `photorec` |
| **Steganography** | `steghide`, `zsteg`, `binwalk`, `exiftool`, `strings` |
| **Active Directory** | `impacket-secretsdump`, `impacket-GetNPUsers`, `crackmapexec`, `smbclient`, `rpcclient`, `bloodhound-python`, `kerbrute`, `netexec` |
| **Windows Internals** | `powershell`, `reg`, `schtasks`, `sc`, `tasklist`, `net user`, `ipconfig` |
| **Linux Privilege Escalation** | `sudo`, `find`, `linpeas`, `linux-exploit-suggester`, `pspy`, `getcap`, `crontab` |
| **Cloud Security** | `aws`, `gcloud`, `az`, `bucket_finder`, `CloudBrute` |
| **Containers** | `docker`, `kubectl`, `cdk`, `amicontained`, `deepce` |
| **Mobile Security** | `apktool`, `jadx`, `adb`, `frida`, `objection` |
| **OSINT** | `theHarvester`, `recon-ng`, `sherlock`, `spiderfoot`, `waybackurls`, `builtwith` |
| **Git** | `git log`, `git show`, `git diff`, `gitleaks`, `truffleHog` |
| **Scripting Helpers** | `python3`, `perl`, `jq`, `yq`, `xargs`, `parallel` |
| **Misc Utilities** | `tmux`, `screen`, `script`, `watch`, `md5sum`, `sha256sum`, `file`, `stat`, `vimdiff`, `xxd` |



#####  Usage Examples

##### Browse All Tools
```bash
$ python cli_fer

      /\_/\
     ( o.o )    CLI Command Lookup
      > ^ <     ~~~~~~~~~~~~~~~~~~
     /_/ \_\

============================================================
   CLI COMMAND LOOKUP — Categories & Tools
============================================================

─── Linux Fundamentals ───
  ls                         List directory contents
  cd                         Change directory
  find                       Search files in hierarchy
  ...

[Tip] Run: python cli_fer <tool_name>  for flags and examples.

      /\_/\
     ( ^.^ )   Happy hacking, human!
      >   <
```


####  Installation

#### Option 1: Direct Download
```bash
wget https://raw.githubusercontent.com/<your-username>/cli_fer/main/cli_fer.py
python cli_fer
```

#### Option 2: Make It Executable (Unix-like)
```bash
mv cli_fer.py cli_fer
chmod +x cli_fer
./cli_fer nmap
```

#### Option 3: Add to PATH (Optional)
```bash
sudo cp cli_fer /usr/local/bin/cli_fer
cli_fer hashcat
```
---
[![Created by Dreaith](https://img.shields.io/badge/Created%20by-Dreaith-purple.svg)]()
[![Date](https://img.shields.io/badge/Date-2025--01--11-lightgrey.svg)]()
