```
╔══════════════════════════════════════════════════════════════════════╗
║                                                                      ║
║   ██╗   ██╗███████╗███╗   ██╗██╗   ██╗     ███████╗██╗  ██╗███████╗ ║
║   ██║   ██║██╔════╝████╗  ██║██║   ██║     ╚══███╔╝██║  ██║██╔════╝ ║
║   ██║   ██║█████╗  ██╔██╗ ██║██║   ██║       ███╔╝ ███████║█████╗   ║
║   ╚██╗ ██╔╝██╔══╝  ██║╚██╗██║██║   ██║      ███╔╝  ██╔══██║██╔══╝   ║
║    ╚████╔╝ ███████╗██║ ╚████║╚██████╔╝     ███████╗██║  ██║███████╗ ║
║     ╚═══╝  ╚══════╝╚═╝  ╚═══╝ ╚═════╝      ╚══════╝╚═╝  ╚═╝╚══════╝ ║
║                                                                      ║
║              bug bounty hunter  ·  offensive security  ·  tool builder ║
║              tiruvannamalai, india  ·  final-year CS student          ║
╚══════════════════════════════════════════════════════════════════════╝
```

> **"break it, report it, fix it. no harm — just protection."**

---

### `> whoami`

I'm **Venu** — a cybersecurity student and bug bounty hunter who builds his own
offensive tooling from scratch. Python, C, Bash. Recon, payloads, reports,
subdomain takeover. Everything open-source, everything zero-dependency where
possible. Currently shipping my final-year project: **TakeoverHunter**.

---

### `> cat /etc/targets`

`HackerOne (venu-sh)` · `Bugcrowd (venu-sh)` · `Web apps` · `APIs` · `Cloud` · `Subdomain takeover`

---

### `> ls ~/arsenal`  — 20+ tools, all open source

| # | Project | What it does | Stack |
|---|---------|--------------|-------|
| 01 | **[takeoverhunter](https://github.com/Venu-exe/takeoverhunter)** ⭐ | Subdomain takeover detector — DNS + HTTP fingerprinting, ~45 services, web UI, SQLite. *Final-year project.* | Python |
| 02 | **[bountycommand](https://github.com/Venu-exe/bountycommand)** | All-in-one bug bounty command center (web, offline, localStorage) | JS |
| 03 | **[payloadforge](https://github.com/Venu-exe/payloadforge)** | Payload generator & mutator — 7 vuln types, 6 encodings, WAF bypass | Python |
| 04 | **[bountyreport](https://github.com/Venu-exe/bountyreport)** | Report generator — CVSS 3.1, 27 templates, 5 platforms | Python |
| 05 | **[bountyrecon](https://github.com/Venu-exe/bountyrecon)** | Zero-dependency Python recon toolkit | Python |
| 06 | **[full-recon](https://github.com/Venu-exe/full-recon)** | Shell pipeline: subfinder → httpx → nuclei | Bash |
| 07 | **[assetmap](https://github.com/Venu-exe/assetmap)** | Fast recon & fingerprinting (favicon, crt.sh, SSL, headers) | C |
| 08 | **[Beast](https://github.com/Venu-exe/Beast)** | Multi-threaded recon — DNS, ports, TLS, headers | C |
| 09 | **[APIFlowHunter](https://github.com/Venu-exe/APIFlowHunter)** | API endpoint discovery (OpenAPI/Postman/JS/GraphQL) | C |
| 10 | **[idor_prober](https://github.com/Venu-exe/idor_prober)** | IDOR vulnerability prober | C |
| 11 | **[JSScope](https://github.com/Venu-exe/JSScope)** | JS scanner — endpoints, secrets, GraphQL schemas | Python |
| 12 | **[JsonExploit](https://github.com/Venu-exe/JsonExploit)** | JSON/API response parser for exposed data | Python |
| 13 | **[httpfuzz](https://github.com/Venu-exe/httpfuzz)** | HTTP fuzzer for param & endpoint discovery | C |
| 14 | **[s3-toolkit](https://github.com/Venu-exe/s3-toolkit)** | S3 bucket public-access & misconfig scanner | Bash |
| 15 | **[SecritScnner](https://github.com/Venu-exe/SecritScnner)** | Secret scanner | Python |
| 16 | **[Portscanner](https://github.com/Venu-exe/Portscanner)** | Multi-threaded TCP port scanner | Python |
| 17 | **[ssh-bruteforce](https://github.com/Venu-exe/ssh-bruteforce)** | SSH credential auditor (authorized) | Python |
| 18 | **[WebTrap](https://github.com/Venu-exe/WebTrap)** | Honeypot / decoy for malicious scanners | Python |
| 19 | **[keylogger](https://github.com/Venu-exe/keylogger)** | Educational input-capture demo | Python |
| 20 | **[picoCTF-PowerAnalysis](https://github.com/Venu-exe/picoCTF-PowerAnalysis-Part1)** | AES CPA exploit (cryptography) | Python |

---

### `> ./now.sh`

```
[+] FINAL-YEAR PROJECT .... TakeoverHunter (shipped, tested, documented)
[+] HUNTING .............. web apps · APIs · cloud · subdomain takeover
[+] BUILDING ............. all-in-one bug bounty workflow
[+] LEARNING ............. red team fundamentals · SOC · threat intel
[+] PLATFORMS ............ HackerOne (venu-sh) · Bugcrowd (venu-sh)
```

---

### `> cat skill_matrix.txt`

```
python  ████████████████████░░  85%   offensive tooling, automation
bash    ██████████████████░░░░  80%   pipelines, tool chaining
web     ███████████████░░░░░░░  75%   XSS, IDOR, SSRF, API security
recon   ███████████████░░░░░░░  75%   subdomain enum, OSINT, fingerprinting
c       ██████████████░░░░░░░░  70%   fast binaries, scanners, fuzzers
soc     ████░░░░░░░░░░░░░░░░░░  25%   learning
redteam ██░░░░░░░░░░░░░░░░░░░░  20%   learning
```

---

### `> cat roadmap.md`

- [x] Build a zero-dependency recon toolkit
- [x] Ship an all-in-one bug bounty command center
- [x] Create a payload generator & mutator with WAF bypass
- [x] Build a multi-platform report generator (CVSS 3.1)
- [x] **Final-year project: TakeoverHunter (subdomain takeover detector)**
- [ ] Publish a bug bounty methodology writeup
- [ ] Add ML-based false-positive filtering to TakeoverHunter
- [ ] Contribute a nuclei template pack
- [ ] First paid Critical finding 🎯

---

### `> cat daily_driver.txt`

```
OS        : Kali Linux (rolling) + Windows (WSL2)
Editor    : VS Code (vim motions)
Shell     : zsh + oh-my-zsh + powerlevel10k
Terminal  : kitty
Recon     : subfinder · httpx · nuclei · naabu · katana
Proxy     : Burp Suite
Langs     : Python · C · Bash · JavaScript
```

---

### `> cat wins.log`

```
[2026]  Subdomain takeover chain  .............  HackerOne   Critical
[2026]  IDOR on API endpoint  ................  Bugcrowd    High
[2026]  Exposed secrets in JS bundle  ........  HackerOne   Medium
[2026]  S3 bucket misconfig (public write) ...  Bugcrowd    Medium
[....]  more in progress
```

> Program names withheld per disclosure policy.

---

### `> cat /etc/contact`

- HackerOne → [venu-sh](https://hackerone.com/venu-sh?type=user)
- Bugcrowd → [venu-sh](https://bugcrowd.com/h/venu-sh)
- GitHub → [Venu-exe](https://github.com/Venu-exe)

**Open to:** collaboration on offensive tooling · bug bounty team-ups (web/API/cloud) · final-year project guidance · open-source security contributions.

---

```
┌─────────────────────────────────────────────────────────────┐
│  "The best way to predict the future is to invent it."      │
│  — but first, break it, report it, and fix it.             │
└─────────────────────────────────────────────────────────────┘
```

---

*No third-party widgets. No badges. Just the work.*