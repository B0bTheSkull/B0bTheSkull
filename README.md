# Hey, I'm Bob — B0bTheSkull

Security researcher and blue team builder. I spend my time breaking things to understand how to defend them — HackTheBox, TryHackMe, bug bounty, and a growing set of tools I've built for real-world use.

**CompTIA Security+** | **CompTIA A+** | Active on [HackTheBox](https://hackthebox.com) & [TryHackMe](https://tryhackme.com)

---

## Tools I've Built

### Blue Team & Detection
| Repo | What it does |
|------|-------------|
| [**SigmaForge**](https://github.com/B0bTheSkull/sigmaforge) | Sigma rule writer, validator, and converter — pySigma-powered CLI that translates portable detection rules to Splunk SPL and Elastic Lucene |
| [**LogHound**](https://github.com/B0bTheSkull/loghound) | CLI log anomaly detector — finds brute force, privilege escalation, and scanner behavior in auth and web server logs (every detection mapped to MITRE ATT&CK) |
| [**NetSentinel**](https://github.com/B0bTheSkull/netsentinel) | Real-time network monitor using Scapy — detects ARP spoofing, port scans, DNS hijacking, ICMP floods, and DNS tunneling |
| [**HoneyNet**](https://github.com/B0bTheSkull/honeynet) | Modular honeypot framework — SSH, HTTP, and FTP decoys with centralized logging and coordinated scan detection |
| [**ThreatPulse**](https://github.com/B0bTheSkull/threatpulse) | Threat intel aggregator — CLI IOC lookup + web dashboard across URLhaus, MalwareBazaar, Feodo Tracker, and OTX |
| [**pihole-lab**](https://github.com/B0bTheSkull/pihole-lab) | Pi-hole + unbound deployment with a DNS-layer detection toolkit (DoH/DoT bypass, canary domains, DGA scoring, Suricata correlation) and Prometheus/Grafana/Loki observability |

### Web & Network Security
| Repo | What it does |
|------|-------------|
| [**WebAudit**](https://github.com/B0bTheSkull/webaudit) | Web app security scanner — checks headers, exposed files, SSL, cookies, XSS reflection, generates HTML reports |
| [**SubScope**](https://github.com/B0bTheSkull/subscope) | Subdomain enumeration — DNS brute force + cert transparency + HTTP probing + takeover detection |

### Threat Hunting & Analysis
| Repo | What it does |
|------|-------------|
| [**PhishKit Analyzer**](https://github.com/B0bTheSkull/phishkit-analyzer) | Static analyzer for suspected phishing pages — detects credential forms, kit fingerprints (16shop, Telegram/Discord exfil), brand impersonation, hidden iframes, and embedded IOCs |
| [**vault-scan**](https://github.com/B0bTheSkull/vault-scan) | Secret scanner for git repositories — ~30 vendor-specific patterns + entropy detection, JSON output, CI-friendly exit codes |
| [**darkdump_crawl**](https://github.com/B0bTheSkull/darkdump_crawl) | Paste & leak extractor — pulls credentials, emails, API keys, crypto wallets, and IOCs from paste dumps |
| [**Cybersecurity-projects**](https://github.com/B0bTheSkull/Cybersecurity-projects) | Collection of smaller tools: password strength + breach checker (HIBP), web metadata scraper, ESP32 evil twin demo |

### Job Market
| Repo | What it does |
|------|-------------|
| [**job-scraper**](https://github.com/B0bTheSkull/job-scraper) | LinkedIn job scraper with fake-job detection and cross-verification |

---

## CTF Writeups

28+ writeups across TryHackMe and HackTheBox — solving challenges and documenting the process for anyone stuck on the same problem.

→ [**All writeups**](https://github.com/B0bTheSkull/CyberSecWriteUps) | [TryHackMe](https://github.com/B0bTheSkull/CyberSecWriteUps/tree/main/THM) | [HackTheBox](https://github.com/B0bTheSkull/CyberSecWriteUps/tree/main/HTB)

---

## Blog

Longer writeups and project breakdowns live on **[BobTheSkull.org](https://www.bobtheskull.org)**.

---

*If something I built is useful to you, star it. If something's broken, open an issue.*
