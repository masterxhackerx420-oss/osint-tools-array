# OSINT Tools Array

![WolfSec Team](https://raw.githubusercontent.com/masterxhackerx420-oss/osint-tools-array/main/wolfsec-team.jpg)

**A large, curated array of Open Source Intelligence (OSINT) tools for beginners to experts.**

> Free-first, categorized, practical. From browser tools you can use in 5 minutes to CLI automation and link-analysis platforms used by professionals.

### Live Interactive Version
**[https://masterxhackerx420-oss.github.io/osint-tools-array/](https://masterxhackerx420-oss.github.io/osint-tools-array/)**

Searchable & filterable tool list.

---

## Philosophy

- **Start with what you have.** Username? Domain? Image? Email? Phone? Pick the matching category.
- **Free tools first.** Most powerful capabilities exist in open-source or free-tier tools.
- **OPSEC always.** Never use your real identity, accounts, or home IP for investigations. Use VPN/Tor, dedicated accounts, and clean browsers.
- **Legal & ethical.** Only public data. Respect platform ToS and local laws. This is for legitimate research, journalism, security, and curiosity — not harassment or illegal activity.
- **Verify everything.** Tools produce leads, not facts. Cross-check. Document sources and timestamps.

**Status checked:** October 2026.

---

## Quick Start Paths

### Beginner (no install, browser only)
1. Learn Google operators (`site:`, `filetype:`, `"exact"`, `-exclude`).
2. Use [OSINT Framework](https://osintframework.com) as your map.
3. Username → [WhatsMyName](https://whatsmyname.app)
4. Email breach → [Have I Been Pwned](https://haveibeenpwned.com)
5. Domain/subdomains → [crt.sh](https://crt.sh)
6. Old pages → [Wayback Machine](https://web.archive.org)
7. Reverse image → Google Lens / TinEye / Yandex
8. Metadata → [ExifTool](https://exiftool.org) (or online viewers)

### Intermediate
- Install Sherlock + Maigret for deep username sweeps.
- Use Shodan / Censys for infrastructure.
- theHarvester + Amass for domain recon.
- Start building graphs in Maltego Community or Obsidian.

### Expert
- Automation with Recon-ng, custom scripts, or maintained frameworks.
- Link analysis (Maltego Pro / i2).
- Dark web monitoring, Intelligence X, dedicated OPSEC environments.
- Case management + evidence capture (Hunchly, ArchiveBox, etc.).

---

## Categories

### 1. Username & Identity Search
| Tool | Level | Type | Notes | Link |
|------|-------|------|-------|------|
| WhatsMyName | Beginner | Web | Fast, curated, no install. ~700+ sites. | [whatsmyname.app](https://whatsmyname.app) |
| Sherlock | Beginner–Int | CLI | Classic. ~400 sites. Fast. `pip install sherlock-project` | [GitHub](https://github.com/sherlock-project/sherlock) |
| Maigret | Intermediate | CLI | Deep. 3000+ sites, profile extraction, recursive, reports. | [GitHub](https://github.com/soxoj/maigret) |
| Namechk | Beginner | Web | Availability checker. | [namechk.com](https://namechk.com) |
| Blackbird | Intermediate | CLI/Web | WhatsMyName-based + extras. | Various |

### 2. Email Address
| Tool | Level | Type | Notes | Link |
|------|-------|------|-------|------|
| Have I Been Pwned | Beginner | Web | Gold standard for breaches. | [haveibeenpwned.com](https://haveibeenpwned.com) |
| EmailRep | Beginner | Web | Reputation signals. | [emailrep.io](https://emailrep.io) |
| theHarvester | Intermediate | CLI | Emails, hosts, subdomains from domain. | [GitHub](https://github.com/laramies/theHarvester) |
| Hunter.io | Intermediate | Web | Finding emails at companies (limited free). | [hunter.io](https://hunter.io) |

*Note: Holehe is unmaintained as of late 2024.*

### 3. Domain, IP & Infrastructure
| Tool | Level | Type | Notes | Link |
|------|-------|------|-------|------|
| crt.sh | Beginner | Web | Certificate transparency → subdomains. | [crt.sh](https://crt.sh) |
| ICANN Lookup / RDAP | Beginner | Web | Registration data (WHOIS is fading). | [lookup.icann.org](https://lookup.icann.org) |
| DNSDumpster | Beginner | Web | Visual DNS map. | [dnsdumpster.com](https://dnsdumpster.com) |
| Shodan | Intermediate | Web/CLI | Search engine for internet devices. Free tier limited. | [shodan.io](https://www.shodan.io) |
| Censys | Intermediate | Web | Hosts, certificates, services. | [censys.io](https://search.censys.io) |
| SecurityTrails | Intermediate | Web | Historical DNS, passive. | [securitytrails.com](https://securitytrails.com) |
| Amass | Expert | CLI | OWASP subdomain enum & mapping. | [GitHub](https://github.com/owasp-amass/amass) |
| Subfinder | Intermediate | CLI | Fast passive subdomain discovery. | [GitHub](https://github.com/projectdiscovery/subfinder) |

### 4. Social Media & People
| Tool | Level | Type | Notes | Link |
|------|-------|------|-------|------|
| OSINT Framework | Beginner | Web | The master map. Start here. | [osintframework.com](https://osintframework.com) |
| Social Searcher | Beginner | Web | Cross-platform search. | [social-searcher.com](https://www.social-searcher.com) |
| Google / X Advanced Search | Beginner | Web | Operators are free power. | Various |
| Pipl / people search engines | Intermediate | Web | Identity resolution (many paid). | Various |
| Bellingcat Toolkit | All | Web | Curated, high-quality notes. | [bellingcat.com](https://www.bellingcat.com) |

### 5. Images, Video, Metadata & Reverse Search
| Tool | Level | Type | Notes | Link |
|------|-------|------|-------|------|
| Google Lens | Beginner | Web | Best free visual search. | [lens.google.com](https://lens.google.com) |
| TinEye | Beginner | Web | Exact & edited matches, oldest first. | [tineye.com](https://tineye.com) |
| Yandex Images | Beginner | Web | Often stronger for faces/people. | [yandex.com/images](https://yandex.com/images) |
| ExifTool | Beginner–Int | CLI | The metadata king. GPS, camera, dates. | [exiftool.org](https://exiftool.org) |
| FotoForensics | Beginner | Web | ELA, JPEG analysis. | [fotoforensics.com](https://fotoforensics.com) |
| InVID / WeVerify | Intermediate | Browser ext | Video verification. | Various |

### 6. Archives & Historical
| Tool | Level | Type | Notes | Link |
|------|-------|------|-------|------|
| Wayback Machine | Beginner | Web | Essential. | [web.archive.org](https://web.archive.org) |
| archive.today | Beginner | Web | Alternative snapshots. | [archive.today](https://archive.ph) |
| CachedView / Google Cache | Beginner | Web | Quick checks. | Various |

### 7. Geolocation, Maps & GEOINT
| Tool | Level | Type | Notes | Link |
|------|-------|------|-------|------|
| Google Earth / Maps | Beginner | Web | Street view, historical imagery. | [earth.google.com](https://earth.google.com) |
| SunCalc | Beginner | Web | Shadow analysis for time/location. | [suncalc.org](https://www.suncalc.org) |
| Copernicus Browser | Intermediate | Web | Satellite (replacement for Sentinel Hub EO). | [browser.dataspace.copernicus.eu](https://browser.dataspace.copernicus.eu) |
| OpenStreetMap / Overpass | Intermediate | Web | Detailed mapping. | [openstreetmap.org](https://www.openstreetmap.org) |

### 8. Breach, Leaks & Dark Web
| Tool | Level | Type | Notes | Link |
|------|-------|------|-------|------|
| Have I Been Pwned | Beginner | Web | Public breaches. | [haveibeenpwned.com](https://haveibeenpwned.com) |
| Intelligence X | Intermediate | Web | Leaks, pastes, darknet. Free tier limited. | [intelx.io](https://intelx.io) |
| DeHashed | Intermediate | Web | Breach search (paid heavy). | [dehashed.com](https://dehashed.com) |
| Ahmia | Intermediate | Web | Onion search engine. | [ahmia.fi](https://ahmia.fi) |

### 9. Frameworks, Automation & Visualization
| Tool | Level | Type | Notes | Link |
|------|-------|------|-------|------|
| Maltego | Intermediate–Expert | Desktop | Gold standard link analysis. Free Community available. | [maltego.com](https://www.maltego.com) |
| Recon-ng | Intermediate | CLI | Modular recon framework. | [GitHub](https://github.com/lanmaster53/recon-ng) |
| SpiderFoot | (Deprecated open-source) | — | Last major release 2022. Use focused tools instead. | — |
| Obsidian | All | Desktop | Excellent for note-taking + graph view of investigations. | [obsidian.md](https://obsidian.md) |
| Draw.io / diagrams.net | Beginner | Web | Free relationship mapping. | [app.diagrams.net](https://app.diagrams.net) |

### 10. Search Engines & Advanced Operators
- Google, DuckDuckGo, Bing, Yandex, Startpage
- Key operators: `site:`, `filetype:`, `intitle:`, `inurl:`, `"phrase"`, `-exclude`, `before:`, `after:`, `AROUND()`
- Google Dorks collections (use responsibly)

### 11. Phone Numbers
- Manual + libphonenumber for validation/formatting
- Carrier lookups via free sites (limited accuracy)
- *PhoneInfoga is unmaintained (last 2024)*

### 12. OPSEC & Learning Resources
- OSINT Framework
- Bellingcat guides & toolkit
- Trace Labs CTFs (practice)
- Michael Bellingcat / IntelTechniques materials
- Your own OPSEC: separate browser profile, VPN, no personal logins

---

## Recommended Beginner Stack (Day 1–7)

| Day | Focus | Tools |
|-----|-------|-------|
| 1 | Map | OSINT Framework + Google operators |
| 2 | Username | WhatsMyName |
| 3 | Email | Have I Been Pwned |
| 4 | Domain | crt.sh + Wayback |
| 5 | Image | TinEye + Google Lens + ExifTool |
| 6 | Social | Advanced search on platforms |
| 7 | Practice | Pick a public target (news story, company, yourself) and document |

---

## Expert Workflows

1. **Username pivot**: WhatsMyName → Sherlock → Maigret → profile extraction → image reverse on avatars → email/phone from bios → breach check.
2. **Domain investigation**: RDAP → crt.sh → DNSDumpster → Amass/Subfinder → Shodan/Censys → Wayback → certificate analysis.
3. **Image geolocation**: Exif (if present) → reverse search → visual landmarks → SunCalc + shadow → Street View confirmation.
4. **Link analysis**: Collect entities → Maltego or Obsidian graph → identify clusters and anomalies.

---

## Disclaimer

This collection is for educational and legitimate research purposes only. Always follow applicable laws and platform terms of service. The authors are not responsible for misuse.

**Contributions welcome.** Open an issue or PR with new tools, status updates, or better categorizations.

---

*Built with LULZ and WolfSec energy. Last major update: October 2026.*
