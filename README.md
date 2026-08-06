# Legal texts for **Daily Quote**

Public legal docs and AdMob `app-ads.txt` for the *Daily Quote* app (Android).

## Files

- `PRIVACY_POLICY.md` – Privacy Policy (EN / UK / RU) for Google Play / App Store.
- `TERMS_OF_USE.md` – Terms of Use (EN / UK / RU).
- `app-ads.txt` – AdMob authorized sellers line (mirror; crawler needs domain root — see below).
- `LICENSE` – MIT for texts in this repository.

## Public URLs (GitHub Pages)

| Document | URL |
| --- | --- |
| Privacy Policy | https://andreyfrigoris.github.io/motivation_app_legal/PRIVACY_POLICY.md |
| Terms | https://andreyfrigoris.github.io/motivation_app_legal/TERMS_OF_USE.md |
| app-ads.txt (this repo) | https://andreyfrigoris.github.io/motivation_app_legal/app-ads.txt |

## AdMob `app-ads.txt` (important)

AdMob crawls **`https://andreyfrigoris.github.io/app-ads.txt`** (root of the developer website **domain**), not the `/motivation_app_legal/` path.

Host the same file at the user GitHub Pages site:

- Repo: `AndreyFrigoris/AndreyFrigoris.github.io`
- File at repo root: `app-ads.txt`
- Live URL: https://andreyfrigoris.github.io/app-ads.txt

In **Google Play Console** → Store listing / developer contact, set **Website** to:

`https://andreyfrigoris.github.io`

(Privacy Policy URL can stay the `/motivation_app_legal/PRIVACY_POLICY.md` link.)

Current AdMob line:

```text
google.com, pub-5308769401439593, DIRECT, f08c47fec0942fa0
```
