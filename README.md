# blocklist-recommendations
# IOC Blocklist Repository

This repository maintains a set of curated blocklists and hash-based IOCs to help defenders identify and block known malicious artifacts.

## 📁 Lists Included

| File         | Description                       |
|--------------|-----------------------------------|
| `domains.txt`| Malicious domains                 |
| `urls.txt`   | Full malicious URLs               |
| `ips.txt`    | IPv4/IPv6 addresses to block      |
| `md5.txt`    | MD5 hashes of malware             |
| `sha1.txt`   | SHA1 hashes of malware            |
| `sha256.txt` | SHA256 hashes of malware          |

## 🎯 Use Cases

- Firewall & Proxy block rules
- IOC enrichment in SIEM/SOAR
- Threat intel feeds for internal detection systems
- Manual lookups during investigations

## 📚 Sources

See [`sources/threat_feeds.md`](./sources/threat_feeds.md) for upstream providers like:
- Shadowserver
- Cyfirma
- Abuse.ch
- etc

## 📜 License

MIT License
