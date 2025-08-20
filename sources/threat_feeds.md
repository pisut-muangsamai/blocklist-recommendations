# 📚 Threat Intelligence Feeds & Sources

This document provides a list of the trusted sources used to populate and validate the IOCs in this repository.

---

## 🌐 Open Intelligence Feeds

| Source Name        | Type             | Description                                                                 | URL                             |
|--------------------|------------------|-----------------------------------------------------------------------------|----------------------------------|
| Abuse.ch           | URL, Hashes      | Feeds like URLhaus, MalwareBazaar for malware distribution infrastructure   | https://abuse.ch/               |
| CyFirma            | Reports, Hashes  | Targeted threat reports on campaigns, especially across the APAC region     | https://www.cyfirma.com/        |
| AlienVault OTX     | All types        | Crowd-sourced threat intel with IOC “pulses” from the community             | https://otx.alienvault.com/     |
| Talos Intelligence | Domain/IP        | Cisco's threat intel feed for malware infrastructure and emerging threats   | https://talosintelligence.com/  |
| ANY.RUN            | Hashes           | Behavioral sandbox reports and malware hashes contributed by analysts       | https://any.run/                |
| PhishTank          | Phishing URLs    | Community-based feed of verified phishing URLs                              | https://phishtank.org/          |
| OpenPhish          | Phishing URLs    | OpenPhish Community Phishing Feed                                           | https://openphish.com/          |
| AhnLab ASEC        | Reports          | Threat research reports from AhnLab Security Emergency response Center      | https://asec.ahnlab.com/        |
| ANY.RUN Blog       | Research Blog    | Threat intelligence and analysis blog from ANY.RUN sandbox                  | https://any.run/cybersecurity-blog/ |
| AttackIQ          | Reports          | Threat emulation and research blog                                          | https://attackiq.com/           |
| Bitdefender Labs   | Reports          | Malware research and global threat analysis                                 | https://bitdefender.com/blog/labs/ |
| Cado Security      | Research Blog    | Cloud and incident response research                                         | https://cadosecurity.com/blog/  |
| CISA Advisories    | Alerts/Reports   | Cybersecurity advisories from US CISA                                       | https://cisa.gov/news-events/cybersecurity-advisories/ |
| CrowdStrike Blog   | Reports          | Threat research, incident response, and adversary profiling                 | https://crowdstrike.com/blog/   |
| Cybereason Labs    | Research Blog    | Campaign analysis and threat research                                        | https://cybereason.com/blog/category/research/ |
| Darktrace Blog     | Research Blog    | AI-driven cyber defense research and case studies                           | https://darktrace.com/blog/     |
| Fortinet Threat Research | Reports   | Threat research and malware analysis by FortiGuard Labs                     | https://fortinet.com/blog/threat-research/ |
| HarfangLab Inside the Lab | Reports | European threat intelligence and malware analysis                           | https://harfanglab.io/en/insidethelab/ |
| Malwarebytes Labs  | Reports          | Malware analysis and threat intelligence                                    | https://malwarebytes.com/blog/threat-intelligence/ |
| Mandiant Blog      | Reports          | Incident response and advanced threat research                              | https://mandiant.com/resources/blog/ |
| McAfee Labs        | Reports          | Threat intelligence from McAfee Labs                                        | https://mcafee.com/blogs/other-blogs/mcafee-labs/ |
| Proofpoint Threat Blog | Reports      | Research on phishing, malware, and social engineering                      | https://proofpoint.com/us/blog  |
| Securelist (Kaspersky) | Reports      | Malware descriptions and threat research                                    | https://securelist.com/tag/malware-descriptions/ |
| IBM X-Force        | Reports          | Threat intelligence research by IBM X-Force                                | https://securityintelligence.com/category/x-force/threat-intelligence/ |
| Cisco Talos Blog   | Reports          | Threat research, malware analysis, and incident response                    | https://blog.talosintelligence.com |
| Trend Micro Research | Reports        | Global research on malware and targeted attacks                            | https://trendmicro.com/en_us/research/ |
| Unit42 (Palo Alto) | Reports          | Threat research and incident response blog                                  | https://unit42.paloaltonetworks.com |
| Nextron Systems    | Reports          | Detection engineering and threat hunting research                           | https://nextron-systems.com/blog/ |
| Team Cymru         | Reports          | Threat intelligence research and botnet tracking                           | https://team-cymru.com/blog/categories/threat-research/ |
| Zscaler Blog       | Reports          | Threat intelligence and cloud security research                            | https://zscaler.com/blogs/      |
| SonicWall Labs     | Reports          | Threat research and malware campaigns                                       | https://blog.sonicwall.com      |
| K7 Labs            | Reports          | Threat research by K7 Computing                                             | https://labs.k7computing.com/   |
| Recorded Future    | Reports          | Threat intelligence insights and analysis                                   | https://recordedfuture.com/blog |
| Sekoia Threat Blog | Reports          | European cyber threat research                                              | https://blog.sekoia.io/category/research-threat-intelligence/ |
| Embee Research     | Reports          | Emerging threat analysis                                                    | https://embee-research.ghost.io |
| NetSPI Blog        | Technical Blog   | Red team, penetration testing, and vulnerability research                   | https://netspi.com/blog/technical/ |
| Huntress Blog      | Reports          | SMB-focused threat intelligence and detection research                      | https://huntress.com/blog       |
| Group-IB Blog      | Reports          | Threat intelligence on financial and cybercrime groups                      | https://group-ib.com/blog       |
| Trellix Research   | Reports          | Threat intelligence and incident response                                   | https://trellix.com/blogs/research |
| Imperva Labs       | Reports          | Application security and research                                           | https://imperva.com/blog/?category=labs |
| ReliaQuest Blog    | Reports          | Threat research and SOC enablement                                          | https://reliaquest.com/blog/    |
| Akamai Research    | Reports          | DDoS, botnet, and edge security research                                    | https://akamai.com              |
| GenDigital Labs    | Reports          | NortonLifeLock/Avast research blog                                          | https://gendigital.com/blog/insights/research |
| Cleafy Labs        | Reports          | Threat research on fraud and malware                                        | https://cleafy.com/labs         |
| GuidePoint Labs    | Reports          | Threat intelligence and red team blogs                                      | https://guidepointsecurity.com/blog/ |
| OpenAnalysis       | Reports          | Malware analysis and reverse engineering                                    | https://research.openanalysis.net |
| Phylum Research    | Reports          | Supply chain and software security research                                 | https://blog.phylum.io/tag/research/ |
| ShadowStack        | Reports          | Malware analysis and reverse engineering                                    | https://shadowstackre.com/analysis/ |
| MSSP Lab           | Reports          | Threat research and blogs                                                   | https://mssplab.github.io       |
| FarghlyMal Blog    | Reports          | Threat research and reverse engineering                                     | https://farghlymal.github.io    |
| ASEC (KR)          | Reports          | Korean version of AhnLab ASEC blog                                          | https://asec.ahnlab.com/ko/     |
| BushidoToken Blog  | Reports          | Independent CTI research and malware analysis                               | https://blog.bushidotoken.net   |
| Kroll Cyber Blog   | Reports          | Cyber incident response and threat intelligence                             | https://kroll.com/en/insights/publications/cyber |
| SentinelOne Labs   | Reports          | Advanced research and threat intelligence                                   | https://sentinelone.com         |
| Lumen Blog         | Reports          | Threat intelligence and security research                                   | https://blog.lumen.com          |

---

## 🧪 Manual & Community-Contributed Sources

These are IOCs contributed by trusted analysts or manually extracted from:
- Threat research blogs and PDF reports
- Security conferences or dark web monitoring insights
- Internal SOC investigations (anonymized/sanitized)
- OSINT posts from verified CTI researchers on Twitter/X, GitHub, etc.

---

## 🛡️ Feed Selection Criteria

We select and verify feeds based on:

- Source credibility and history
- Frequency and recency of updates
- Context provided (malware name, campaign, TTP, etc.)

---

## 📝 Notes

- We do **not** include:
  - Wildcard domains (e.g., `*.example.com`)
  - Cloud service providers (e.g., `*.google.com`, `*.microsoft.com`)
  - Content delivery networks (CDNs)
- All entries are normalized and deduplicated during ingestion

If you would like to suggest a new threat intel source, please [open an issue](https://github.com/pisut-muangsamai/blocklist-recommendations/issues) or submit a pull request to this file.
