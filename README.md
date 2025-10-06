# Security Learning Roadmap

_From SWE to SWE Security Professional or something_

---

## 🎯 Overview

**Background:** 10 years software engineering experience (FE/BE/OPS)  
**Goal:** Fullfil childhood passion for hacking + leverage SWE skills into security  
**Approach:** Systematic, foundational learning with daily practice  
**Timeline:** ~12-18 months for complete roadmap

---

## 📚 Book Inventory

### Purchased Books (£158 total)

#### Network Fundamentals

- [ ] [[Practical Packet Analysis]] - £21.99
- [ ] [[TCP IP Illustrated]] - £34.73

#### Web Application Security

- [ ] [[Bug Bounty Bootcamp]] - £19.99
- [ ] [[Hacking APIs]] - £25.99

#### Secure Development

- [ ] [[Alice and Bob Learn Application Security]] - £27.77
- [ ] [[Alice and Bob Learn Secure Coding]] - £26.50

#### Offensive Security & Red Team

- [ ] [[Red Team Development and Operations]] - £10.05
- [ ] [[Operator Handbook]] - £12.18
- [ ] [[Adversarial Tradecraft]] - £32.99
- [ ] [[Hacker Playbook 3]] - £14.31

### Future Considerations (Hold until Phase 5)

- [ ] Penetration Testing Azure for Ethical Hackers (~£25-35)
- [ ] Hands-On AWS Penetration Testing with Kali Linux (~£30-40)
- [ ] Hacking Kubernetes (~£25-35)

### Reference (Free/Optional)

- Security Engineering by Ross Anderson - _Free PDF available_
- Threat Modeling by Adam Shostack - _Revisit in 6-12 months_

---

## 🗺️ Learning Path

### Phase 1: Network Fundamentals (Current Phase)

**Timeline:** 4-8 weeks  
**Status:** 🟢 In Progress

#### Active Study

- [x] Practical Networking Fundamentals Course
    - Video lectures with active note-taking
    - Flashcard creation for key concepts
    - Regular review sessions

#### Books

- [ ] [[Practical Packet Analysis]]
    - Hands-on Wireshark practice
    - Analyze real network traffic
    - Build packet analysis skills
- [ ] [[TCP IP Illustrated]]
    - Read relevant chapters alongside Practical Packet Analysis
    - Use as reference material
    - Deep dive into protocol mechanics

#### Free Learning Resources

**YouTube Channels:**
- [Practical Networking](https://www.youtube.com/watch?v=bj-Yfakjllc&list=PLIFyRwBY_4bRLmKfP1KnZA6rZbRHtxmXi) - Clear visual explainers for TCP/IP, subnetting, routing
- [Professor Messer Security+](https://www.professormesser.com/security-plus/sy0-601/sy0-601-training-course/) - Free structured networking lessons
- [NetworkChuck](https://www.youtube.com/@NetworkChuck) - Beginner-friendly protocols, subnetting, VLANs
- [David Bombal](https://www.youtube.com/@davidbombal) - Networking + security context, Wireshark tutorials

**Completion Criteria:**

- Can explain TCP/IP stack confidently
- Comfortable capturing and analyzing packets in Wireshark
- Understand common network protocols (HTTP, DNS, TCP, UDP, etc.)

---

### Phase 2: Web Application Security

**Timeline:** 8-12 weeks  
**Why This Phase:** Leverages existing dev knowledge, immediate practical value

#### Books & Labs

1. [ ] [[Bug Bounty Bootcamp]]
    - Modern web vulnerabilities (SQLi, XSS, CSRF, etc.)
    - Hands-on with bug bounty programs
    - Set up personal lab environment
2. [ ] [[Hacking APIs]]
    - API-specific attack vectors
    - REST/GraphQL security
    - Authentication/authorization flaws
3. [ ] [[Alice and Bob Learn Secure Coding]]
    - Secure coding patterns
    - Input validation, output encoding
    - Common pitfalls in code

**Free Platforms:**
- [PortSwigger Web Security Academy](https://portswigger.net/web-security) - Free hands-on labs
- [OWASP Top 10](https://owasp.org/www-project-top-ten/) - Security risk reference
- [OWASP Web Security Testing Guide](https://owasp.org/www-project-web-security-testing-guide/) - Comprehensive testing framework

**Practical Activities:**

- Sign up for HackerOne/Bugcrowd
- Practice on legal targets (HackTheBox, PortSwigger Academy)
- Set up DVWA, WebGoat for local practice
- Document findings in security journal

**Tools to Master:**
- Burp Suite (Community Edition)
- Browser DevTools
- sqlmap
- Postman/Insomnia (API testing)

**Completion Criteria:**

- Found at least 3-5 vulnerabilities in practice platforms
- Understand OWASP Top 10 deeply
- Can identify common web app vulnerabilities in code reviews

---

### Phase 3: Red Team Operations

**Timeline:** 8-10 weeks  
**Why This Phase:** Now you understand web apps, learn how attackers operate

#### Books

1. [ ] [[Operator Handbook]]
    - Quick reference for tools and techniques
    - Command cheat sheets
    - OSINT fundamentals
2. [ ] [[Hacker Playbook 3]]
    - Penetration testing methodology
    - Attack chains and lateral movement
    - Real-world engagement scenarios
3. [ ] [[Red Team Development and Operations]]
    - Building red team infrastructure
    - Operational security
    - Command and control frameworks
4. [ ] [[Adversarial Tradecraft]]
    - Advanced red team tactics
    - Evasion techniques
    - Threat actor methodologies

**Practical Activities:**

- Build home lab (VirtualBox/VMware)
- Practice on VulnHub VMs
- Set up red team infrastructure
- Join HTB or TryHackMe

**Platforms:**
- [TryHackMe](https://tryhackme.com/paths) - Guided exercises (~£100/year Premium)
- [Hack The Box](https://www.hackthebox.com/) - Realistic boxes (~£100/year VIP)
- [PentesterLab Pro](https://pentesterlab.com/pro) - Curated exercises (~£20/month, optional)

**Essential Tools:**
- nmap (reconnaissance)
- gobuster/feroxbuster (directory enumeration)
- Metasploit Framework
- Bloodhound (Active Directory)
- PEASS-ng (privilege escalation)

**Completion Criteria:**

- Can conduct full penetration test methodology
- Understand attack chains and privilege escalation
- Comfortable with Metasploit, Burp Suite, common tools

---

### Phase 4: Application Security Architecture

**Timeline:** 4-6 weeks  
**Why This Phase:** Synthesize offensive + defensive knowledge

#### Books

1. [ ] [[Alice and Bob Learn Application Security]]
    - Threat modeling frameworks
    - Security in SDLC
    - Architecture-level security decisions

**Practical Activities:**

- Threat model a personal project
- Design security architecture for hypothetical systems
- Review past projects with security lens

**Completion Criteria:**

- Can perform threat modeling exercises
- Understand secure architecture patterns
- Can lead security discussions in engineering teams

---

### Phase 5: Cloud & Container Security

**Timeline:** 8-12 weeks  
**Why Last:** Builds on all previous knowledge

#### Books (Purchase when ready)

1. [ ] Hacking Kubernetes
    - Container security
    - K8s-specific attack vectors
    - Cloud-native security
2. [ ] Penetration Testing Azure OR AWS
    - Choose based on work environment
    - Cloud pentesting methodology
    - IAM and cloud-specific vulnerabilities

**Practical Activities:**

- Set up personal cloud lab (free tier AWS/Azure)
- Deploy intentionally vulnerable cloud apps
- Practice cloud pentesting techniques

**Free Practice Labs:**
- [Kubernetes Goat](https://madhuakula.com/kubernetes-goat/) - Vulnerable K8s cluster by design
- [Canarytokens](https://canarytokens.org/generate) - Detection lab for defensive practice
- AWS/Azure free tier accounts

**Learning Platforms:**
- [A Cloud Guru](https://acloudguru.com/) - AWS/Azure security courses (~£300/year)

**Completion Criteria:**

- Understand cloud security models
- Can identify cloud misconfigurations
- Familiar with cloud pentesting tools

---

## 🛠️ Parallel Activities

### Daily Habits

- [ ] 30-60 minutes security study/practice
- [ ] Flashcard review (spaced repetition)
- [ ] Document learnings in security journal

### Weekly Goals

- [ ] Complete X pages/chapters of current book
- [ ] Solve 2-3 CTF challenges
- [ ] Write 1 blog post or note summarizing learnings

### Ongoing Skill Development

- [ ] **Rust Programming** - Continue deepening systems programming knowledge
    - Systems programming + security = powerful combination
    - Low-level understanding helps with exploitation
- [ ] **CTF Participation** - Regularly practice on platforms
    - HackTheBox, TryHackMe, PortSwigger Academy
    - Real-world skill validation
- [ ] **Security Community** - Engage with the community
    - Follow security researchers on Twitter/Mastodon
    - Read security blogs and vulnerability disclosures
    - Attend local security meetups (if available)

---

## 🎓 Certifications (Optional - After Phase 3)

_Consider these once you have solid foundational knowledge:_

- **OSCP** (Offensive Security Certified Professional)
    - Gold standard for pentesting
    - Hands-on 24-hour exam
- **eWPT** (eLearnSecurity Web Application Penetration Tester)
    - Web app focus
    - More accessible than OSCP
- **CEH** (Certified Ethical Hacker)
    - Broader but less hands-on
    - Good for HR checkboxes

**Note:** Books + practical experience may be more valuable than certs depending on career goals.

---

## 🚫 What's Missing? Critical Gaps to Address

### 1. Active Directory / Windows Security

**Why It Matters:** Most enterprise environments run on AD  
**When to Add:** After Phase 3  
**Resource Suggestions:**

- Look for AD exploitation content
- Practice with Bloodhound, PowerView
- Study Kerberos attacks (Golden/Silver tickets)

### 2. Binary Exploitation / Reverse Engineering

**Why It Matters:** Low-level exploitation, malware analysis  
**Current Status:** Not in current roadmap (intentional)  
**Decision:** Skip unless specific interest emerges  
**Alternative:** Your Rust knowledge gives you systems understanding

### 3. Wireless Security

**Why It Matters:** Physical security assessments  
**Current Status:** Not covered  
**Decision:** Skip unless needed for specific role

### 4. Mobile Application Security (iOS/Android)

**Why It Matters:** Mobile apps are everywhere  
**Current Status:** Not covered  
**Decision:** Consider if relevant to work, otherwise skip

### 5. Hands-On Lab Time

**Critical:** Books alone are insufficient  
**Action Items:**

- Set up home lab NOW (even basic VirtualBox setup)
- Practice alongside reading, not after
- Budget lab time equal to reading time

### 6. Community Engagement

**Why It Matters:** Learning alone is hard, community accelerates growth  
**Action Items:**

- Join Discord servers (HackTheBox, Security communities)
- Follow security researchers
- Participate in writeup discussions

---

## 📊 Progress Tracking

### Phase Completion

- [ ] Phase 1: Network Fundamentals
- [ ] Phase 2: Web Application Security
- [ ] Phase 3: Red Team Operations
- [ ] Phase 4: Application Security Architecture
- [ ] Phase 5: Cloud & Container Security

### Skill Checkpoints

_Self-assess quarterly_

|Skill Area|Q1|Q2|Q3|Q4|
|---|---|---|---|---|
|Network Fundamentals|⬜|⬜|⬜|⬜|
|Web App Security|⬜|⬜|⬜|⬜|
|Penetration Testing|⬜|⬜|⬜|⬜|
|Secure Development|⬜|⬜|⬜|⬜|
|Red Team Ops|⬜|⬜|⬜|⬜|
|Cloud Security|⬜|⬜|⬜|⬜|

**Legend:** ⬜ Not Started | 🟡 Learning | 🟢 Competent | 🔵 Proficient

---

## 💡 Key Principles

### 1. Depth Over Breadth

- Master one area before moving to next
- 30-60 min daily beats 4-hour weekend binges
- Finish books, don't collect them

### 2. Practice While Learning

- Don't just read — hack
- Set up labs alongside reading
- Every concept needs hands-on validation

### 3. Document Everything

- Take notes in Obsidian
- Write blog posts or internal documentation
- Build personal knowledge base

### 4. Learn in Public

- Share findings (responsibly)
- Contribute to community
- Teaching solidifies knowledge

### 5. Sustainable Pace

- 12-18 month roadmap is realistic
- Life happens, adjust timeline as needed
- Consistency beats intensity

---

## 🔄 Review Schedule

### Weekly Review (Every Sunday)

- What did I learn this week?
- What challenges did I face?
- What's the plan for next week?
- Update progress tracking

### Monthly Review (Last Sunday of Month)

- Review flashcards and notes
- Assess if on track with current phase
- Adjust timeline if needed
- Celebrate wins

### Quarterly Review (Every 3 Months)

- Major skill assessment
- Update roadmap based on interests/career goals
- Consider adding/removing topics
- Plan next quarter

---

## 🎯 Success Metrics

### Short-term (3-6 months)

- Complete Phase 1 & 2
- Find 5+ vulnerabilities on practice platforms
- Build home lab environment
- Start security blog/notes

### Medium-term (6-12 months)

- Complete Phase 3 & 4
- Contribute to bug bounty programs
- Complete 20+ CTF challenges
- Can perform basic penetration test

### Long-term (12-18 months)

- Complete all 5 phases
- Confidently apply security knowledge at work
- Find legitimate bugs in bug bounty programs
- Consider career transition to security role (if desired)

---

## 📝 Notes

### Current Status

- ✅ Book inventory finalized
- ✅ Roadmap created
- 🟢 Currently in Phase 1 (Practical Networking course)
- 🔄 Next: Practical Packet Analysis + TCP/IP Illustrated

### Key Decisions Made

- ✅ Skipping Web App Hacker's Handbook (redundant with Bug Bounty Bootcamp)
- ✅ Keeping both Alice & Bob books (complementary focus)
- ✅ Deferring cloud books until Phase 5
- ✅ Skipping Social Engineering (not technical priority)
- ✅ Using free PDF for Security Engineering

### Questions to Revisit

- [ ] Azure vs AWS for cloud book? (Decide in Phase 4)
- [ ] Need Active Directory book? (Assess after Phase 3)
- [ ] Certification path? (Decide after Phase 3)

---

_Last Updated: 2025-10-06_