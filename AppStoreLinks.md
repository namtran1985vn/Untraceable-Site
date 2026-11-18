# Untraceable public links

Stable URLs for App Store Connect, the app and customer messages.

| Use | URL |
|---|---|
| Marketing URL | https://namtran1985vn.github.io/Untraceable-Site/ |
| Support URL | https://namtran1985vn.github.io/Untraceable-Site/support/ |
| Privacy Policy URL | https://namtran1985vn.github.io/Untraceable-Site/privacy/ |
| Terms of Use | https://namtran1985vn.github.io/Untraceable-Site/terms/ |
| Apple Standard EULA | https://www.apple.com/legal/internet-services/itunes/dev/stdeula/ |
| Support issues | https://github.com/namtran1985vn/Untraceable-Site/issues |

The app links to Privacy and Terms from its paywall and Settings (`Untraceable/Domain/StoreProducts.swift`).

## Before release

- [ ] Set `support_email` in `_config.yml` (the support page falls back to GitHub issues while it is empty).
- [ ] Set `app_store_url` in `_config.yml` once the App Store page exists; the "Coming soon" buttons switch to a download link.
- [ ] Fill the copyright holder, trial length and prices in `app-store/metadata.md`.
- [ ] Re-read `privacy.md` if the app ever adds analytics, an SDK, an account or a network call.
