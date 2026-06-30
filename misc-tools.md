# Misc Tools

Geolocation, EXIF analysis, recon tools, and other utilities that don't fit neatly into a single category.

---

## EXIF & Image Metadata

| Tool | URL | Notes |
|------|-----|-------|
| EXIF.tools | [exif.tools](https://exif.tools) | Extract EXIF metadata from uploaded images (GPS, device, timestamp) |
| GeoImgr | [geoimgr.com](https://www.geoimgr.com) | Map EXIF GPS data to a location |

> If a photo has GPS coordinates in its EXIF data, GeoImgr will plot the exact location on a map.

---

## Canary Tokens

| Tool | URL | Notes |
|------|-----|-------|
| Canary Tokens | [canarytokens.org](https://canarytokens.org/nest/) | Generate tracking tokens (URL, doc, email) that notify you when opened |

> Pair with a URL shortener to disguise the canary link. Useful for confirming if a subject is active or tracking who opens a shared document.

---

## Pastebin / Leak Sites

| Tool | URL | Notes |
|------|-----|-------|
| Pastebin | [pastebin.com](https://pastebin.com) | Search for leaked data, credentials, or mentions of a target |
| PwnBin | [GitHub](https://github.com/kahunalu/pwnbin) | Searches Pastebin and other paste sites for keywords |

---

## Automated Recon

| Tool | URL | Notes |
|------|-----|-------|
| Geo-Recon | [GitHub](https://github.com/radioactivetobi/geo-recon) | Geolocation OSINT tool |
| ReconDog | [GitHub](https://github.com/s0md3v/ReconDog) | Multi-module recon tool (whois, DNS, ports, etc.) |
| Osiris AI | [osirisai.live](https://osirisai.live) | AI-assisted OSINT recon |

---

## Tips

- Always strip EXIF before sharing photos taken during fieldwork — your GPS coords may be embedded
- Canary tokens are most effective when embedded in documents sent to a subject or uploaded to a shared space
- PwnBin is useful for monitoring paste sites for mentions of a client's name or email
