# Website OSINT

Tools for investigating websites, domains, archived pages, and embedded documents.

---

## Website Crawling / Mirroring

| Tool | URL | Notes |
|------|-----|-------|
| SpiderFoot | [GitHub](https://github.com/smicallef/spiderfoot) | Automated OSINT recon; scans IPs, domains, emails |
| HTTrack | [httrack.com](https://www.httrack.com) | Download a full copy of a website |
| Wget (Windows) | [gnuwin32.sourceforge.net](https://gnuwin32.sourceforge.net/packages/wget.htm) | Command-line site mirroring on Windows |

---

## Webpage Archives / Cache

| Tool | URL | Notes |
|------|-----|-------|
| Wayback Machine | [archive.org](https://archive.org) | Historical snapshots of websites |
| Archive.ph | [archive.ph](https://archive.ph) | On-demand page archiving; share a frozen snapshot |

> **Best practice:** Archive a page immediately when found — subjects regularly delete content once they know they're being investigated.

---

## Document Hunting

| Tool | URL | Notes |
|------|-----|-------|
| Metagoofil (GitHub) | [github.com/opsdisk/metagoofil](https://github.com/opsdisk/metagoofil) | Extracts metadata from publicly accessible documents |
| Metagoofil (Kali) | [kali.org/tools/metagoofil](https://www.kali.org/tools/metagoofil/#metagoofil-1) | Kali Linux package docs |

> Metagoofil finds PDFs, Word docs, spreadsheets, etc. indexed on a target domain and pulls metadata (author names, usernames, software versions, etc.)

---

## URL & Domain Analysis

| Tool | URL | Notes |
|------|-----|-------|
| Meta/Narka URL Analyzer | [meta.narka.io](https://meta.narka.io) | Extract metadata and links from a URL |
| DotDB Domain Search | [dotdb.com](https://dotdb.com) | Search domain registrations and related domains |

---

## Tips

- Combine Metagoofil with `site:` Google dorks to find all public documents on a domain
- Use HTTrack before confronting a subject — websites disappear fast
- Check Archive.org for old versions of a site that may reveal past ownership or content
