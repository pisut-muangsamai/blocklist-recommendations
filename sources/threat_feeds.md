# 📚 Threat Intelligence Feeds & Sources

This document provides a list of the trusted sources used to populate and validate the IOCs in this repository.

We include both **high-confidence** and **medium-confidence** IOCs based on source reputation, context, and verification level.

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

---

## 🧪 Manual & Community-Contributed Sources

These are IOCs contributed by trusted analysts or manually extracted from:
- Threat research blogs and PDF reports
- Security conferences or dark web monitoring insights
- Internal SOC investigations (anonymized/sanitized)
- OSINT posts from verified CTI researchers on Twitter/X, GitHub, etc.

We **also include medium-confidence IOCs**, especially when tied to emerging threats or region-specific campaigns.

---

## 🛡️ Feed Selection Criteria

We select and verify feeds based on:

- Source credibility and history
- Frequency and recency of updates
- Confidence level of IOCs (we label them accordingly)
- Context provided (malware name, campaign, TTP, etc.)

---

## 📝 Notes

- Deprecated or inactive sources are removed and archived regularly
- We do **not** include:
  - Wildcard domains (e.g., `*.example.com`)
  - Cloud service providers (e.g., `*.google.com`, `*.microsoft.com`)
  - Content delivery networks (CDNs)
- All entries are normalized and deduplicated during ingestion

If you would like to suggest a new threat intel source, please [open an issue](https://github.com/pisut-muangsamai/blocklist-recommendations/issues) or submit a pull request to this file.
