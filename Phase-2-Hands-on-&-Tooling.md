# (4–6 weeks)

## Why
Move from puzzle labs → realistic messy boxes. Build fluency in tools.

## Resources

### Platforms
- [TryHackMe Web Path](https://tryhackme.com/paths) – guided exercises. Premium ~£100/year.
- [Hack The Box VIP](https://www.hackthebox.com/pricing) – realistic boxes. VIP ~£100/year.
- [PentesterLab Pro](https://pentesterlab.com/pro) – curated exercises. ~£20/month.

### Tools
- [Burp Suite](https://portswigger.net/burp) (Community free / Pro ~£300, skip Pro at first)
- [nmap](https://nmap.org/)
- [gobuster](https://github.com/OJ/gobuster) / [feroxbuster](https://github.com/epi052/feroxbuster)
- [sqlmap](http://sqlmap.org/)
- [PEAS suite](https://github.com/carlospolop/PEASS-ng)

### Books (Optional Advanced Reading)

**Reverse Engineering Focus:**

**"Practical Malware Analysis"** by Sikorski & Honig (~£35)
- **Industry standard** for malware reverse engineering
- Hands-on approach to dissecting malicious software
- Prerequisites: basic C/C++, x86 assembly understanding
- Phase 3-4 material (skip for now unless interested in malware)

**"Practical Binary Analysis"** by Dennis Andriesse (~£35)
- Linux-focused binary analysis and tool building
- Advanced topics: binary instrumentation, taint analysis, symbolic execution
- Hands-on with Pin, libdft, Triton frameworks
- Includes VM with all examples
- Best for: Those wanting to build custom analysis tools

**"Practical Reverse Engineering"** by Dang, Gazet & Bachaalany (~£40)
- Windows kernel focus (x86, x64, ARM)
- Rootkits, drivers, VM protection techniques
- More advanced code obfuscation
- Best for: Windows-focused security engineers

**"The Ghidra Book"** by Chris Eagle (~£35)
- Free open-source alternative to IDA Pro
- Beginner → advanced Ghidra usage
- Same author as "The IDA Pro Book"
- Best for: Those preferring free tools

**"Ghidra Software Reverse-Engineering for Beginners" (2nd Ed)** (~£30)
- Published Jan 2025 – most current
- Covers remote/kernel debugging, binary diffing
- Malware unpacking to ransomware analysis
- More accessible than Eagle's book

#### When to Study Reverse Engineering
- **Phase 2:** Only if HTB boxes require basic binary exploitation
- **Phase 3-4:** Add if pursuing malware analysis or binary exploitation specialization
- **Skip entirely:** If focusing purely on web/cloud pentesting

#### Budget Recommendation
**For web pentesting:** Skip RE books, focus on tools + platforms
**For malware path:** "Practical Malware Analysis" + "Ghidra for Beginners" (~£65)
**For tool building:** "Practical Binary Analysis" (~£35)

## Deliverables
- 6+ HTB reports (steps, PoC, impact, fix).
- “Findings library” (payloads, bypasses, wordlists).

## Checklist
- [ ] Finish THM Web Path
- [ ] Hack 2 easy HTB boxes
- [ ] Hack 4 medium HTB boxes
- [ ] Write 6 full reports
- [ ] Build findings library in Obsidian
