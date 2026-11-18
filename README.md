# Untraceable Site

Public pages for **Untraceable – for Creators**, the iPhone app that makes clean copies of photos and videos on the device. Hosted on GitHub Pages with Jekyll.

| Page | URL |
|---|---|
| Home (Marketing URL) | https://namtran1985vn.github.io/Untraceable-Site/ |
| Support | https://namtran1985vn.github.io/Untraceable-Site/support/ |
| Privacy Policy | https://namtran1985vn.github.io/Untraceable-Site/privacy/ |
| Terms of Use | https://namtran1985vn.github.io/Untraceable-Site/terms/ |

## What's here

| Path | What it is |
|---|---|
| `index.html`, `support/`, `privacy.md`, `terms.md` | The pages |
| `_layouts/default.html`, `assets/site.css` | One layout and one stylesheet, using the app's colours |
| `assets/` | App icon, illustrations from the app's design, and app screenshots. Everything is self-hosted: no web fonts, analytics or third-party embeds |
| `_config.yml` | Site URL, `support_email` and `app_store_url` |
| `AppStoreLinks.md` | The URLs for App Store Connect and the release checklist (not published) |
| `app-store/` | App Store Connect copy and 6.9-inch screenshots (not published) |

## Preview locally

```bash
bundle exec jekyll serve --baseurl /Untraceable-Site
```

Requires the `github-pages` gem (`gem install bundler github-pages`).

## Rules for the copy

- Say exactly what the app removes, and show its limits wherever it describes itself.
- Never promise a file can't be traced. Avoid "undetectable", "guaranteed", "spoof", "bypass".
- No adult terms or platform names, and no real photos or people in images.
- The privacy policy must match the app: no data collected, no network, no SDKs.
