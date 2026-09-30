# fullbacksoftware.com.au

The Fullback Software website, hosted free on GitHub Pages from this public repo. It's plain HTML and one stylesheet, with no build step.

| Page | Address | File |
| :- | :- | :- |
| Home | https://fullbacksoftware.com.au/ | `index.html` |
| Match Manager (App Store marketing URL) | https://fullbacksoftware.com.au/matchmanager | `matchmanager/index.html` |
| Support (App Store support URL) | https://fullbacksoftware.com.au/support | `support/index.html` |
| Privacy policy (App Store privacy policy URL) | https://fullbacksoftware.com.au/privacy | `privacy/index.html` |
| Page not found | Any missing address | `404.html` |

## Changing the site

- Edit the HTML files and commit to `main`. GitHub Pages republishes within a few minutes.
- The header and footer are repeated in every page, so change all five files when you change one.
- Styles live in `assets/site.css`. The brand colours are navy #0E1A2B and chalk #F7F5EF. Bib orange #FF6B1A is only for the fullback dot, never text.
- When the privacy policy changes, update its "Last updated" date too.
- Update the year in the footer each January.

## Rules

- This repo is public. Never add real player, parent or club names, the home address, or anything personal.
- No analytics, trackers, cookies or third-party scripts and fonts. The privacy policy says the site loads nothing from other websites.
- Keep the support email and the PO Box current: Apple requires working contact details on the support page.

## Files

- `CNAME`: the custom domain, fullbacksoftware.com.au.
- `_config.yml`: stops this README being published as a page.
- `favicon.ico`, `favicon.svg`, `apple-touch-icon.png`: the navy icon from the Fullback logo kit.
- `assets/img`: logos from the logo kit, the pitch illustration and the social preview image.
- `assets/fonts`: Poppins, subset for the web, under the SIL Open Font License (`OFL.txt`).

## DNS at VentraIP

| Type | Hostname | Value |
| :- | :- | :- |
| A | (blank) | 185.199.108.153 |
| A | (blank) | 185.199.109.153 |
| A | (blank) | 185.199.110.153 |
| A | (blank) | 185.199.111.153 |
| AAAA (optional) | (blank) | 2606:50c0:8000::153, 2606:50c0:8001::153, 2606:50c0:8002::153, 2606:50c0:8003::153 |
| CNAME | www | fullback-software.github.io |
| TXT | _github-pages-challenge-fullback-software | The code GitHub gives when verifying the domain. Keep it. |

Leave the Google Workspace email records (MX, SPF, DKIM and DMARC) alone. Don't add wildcard (`*`) records.
