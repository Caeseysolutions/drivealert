# DriveAlert — Changelog

All notable changes to drivealert.eu and drivealert.be are documented here.

---

## [2.1.0] — 2026-03-20

### Added
- **Geo-routing** — automatic country detection via ipapi.co (free, no API key)
- Visitors from NL and BE now land on Amazon.nl affiliate links (CO-DRIVER ★10% commission)
- Visitors from FR now land on Amazon.fr affiliate links
- Visitors from GB/IE now land on Amazon.co.uk affiliate links
- DE/AT/CH and all other countries default to Amazon.de (unchanged)
- Manual language selection always overrides geo-detection
- Silent 3-second timeout fallback — geo failure never breaks the page

### Fixed
- **Revenue leak fixed** — previously ALL visitors hit Amazon.de regardless of country
- NL/BE visitors were missing the 10% CO-DRIVER commission (now corrected)

### Affiliate tags confirmed live
- DE: `drivealert-21`
- FR: `drivealert0f-21`
- NL: `drivealert-nl-21`
- UK: `drivealert0a-21`

---

## [2.0.0] — 2026-02-xx

### Added
- Full multilingual support EN / NL / FR / DE
- Legal status tables by country and region
- Media gallery with OOONO official product images and videos
- How-it-works tab switcher (P-DISC / CO-DRIVER)
- FAQ accordion
- Markets section — primary, expansion, overseas territories
- Privacy Policy modal
- Disclaimer modal
- Nextbase 622GW dashcam section (Product 03)
- Structured data / JSON-LD for SEO (Products + FAQPage)
- hreflang tags for multilingual SEO

### Products covered
- OOONO P-DISC NO3
- OOONO CO-DRIVER NO2
- Nextbase 622GW dashcam

---

## [1.0.0] — 2025-xx-xx

### Added
- Initial DriveAlert site launch
- Basic product pages for OOONO P-DISC and CO-DRIVER
- Amazon.de affiliate links (DE only)
- Google Analytics (G-NX1B2429ZH)

---

## Deployment notes

**Repos:** github.com/Caeseysolutions/drivealert · github.com/Caeseysolutions/drivealert.be
**Hosting:** GitHub Pages / Cloudflare
**Analytics:** G-NX1B2429ZH
**Affiliate programme:** Amazon Associates
- DE: drivealert-21
- FR: drivealert0f-21
- NL: drivealert-nl-21
- UK: drivealert0a-21
