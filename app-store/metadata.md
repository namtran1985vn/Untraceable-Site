# App Store Connect — Untraceable 1.0

Copy for App Store Connect. This folder is not published on the website.

## App information

| Field | Value |
|---|---|
| Name (30) | Untraceable – for Creators |
| Subtitle (30) | Clean Photos & Videos to Post |
| Primary category | Photo & Video |
| Secondary category | Utilities |
| Content rights | Does not contain, show or access third-party content |
| Age rating | 4+ (answer "None" to every content question; no unrestricted web access, no user-generated content shown in the app) |
| Copyright | 2026 *[owner or company name]* |

## URLs

| Field | URL |
|---|---|
| Marketing URL | https://namtran1985vn.github.io/Untraceable-Site/ |
| Support URL | https://namtran1985vn.github.io/Untraceable-Site/support/ |
| Privacy Policy URL | https://namtran1985vn.github.io/Untraceable-Site/privacy/ |
| Terms of Use (EULA) | Apple's Standard EULA (leave App Store Connect's custom EULA empty): https://www.apple.com/legal/internet-services/itunes/dev/stdeula/ |

## Promotional text (170)

Clean copies of your photos and videos, made on your iPhone. Location, phone model, dates, names and extra tracks removed. Picture and sound stay the same.

## Keywords (100)

metadata,exif,remover,gps,location,privacy,strip,geotag,watermark,leak,trace,serial,scrub,share

## Description (4000)

Share the picture, not what's hidden in the file.

Phones and editing apps write details into every photo and video: where it was taken, which phone and lens, serial numbers, the date and time, your name, and extra tracks inside videos. Untraceable makes a clean copy before you post or send it. Everything runs on your iPhone. The picture and sound stay the same.

WHAT GETS REMOVED
• Location and capture time, including location tracks in videos
• Phone make and model, lens details, serial numbers and software version
• Owner and author names, captions and editing data
• Linking IDs from Live Photos, bursts and editing apps
• Embedded previews, depth data, content credentials and maker notes
• Extra video tracks: a clean video keeps one picture track and one sound track
• Camera file names like IMG_4821, and the file's own dates

CHECKED BEFORE YOU SHARE
Every clean copy is opened again and checked before you can share or save it. A copy that fails the check is deleted, never handed to you. The report shows exactly what was found and removed.

NOTHING LEAVES YOUR IPHONE
• No account, no uploads, no server
• No analytics, ads or trackers
• Uses the system picker, so the app never reads your photo library
• Originals are deleted from the app once cleaned, and clean copies when you tap Done

UNTRACEABLE PRO
Cleaning one item at a time is free, with every removal included. Pro adds:
• Per-buyer mark: a random code tiled across the picture for one recipient. If a copy leaks, type the code to see who it was made for. The recipient list stays on your iPhone.
• Device unlinking: normalises size and softens sensor noise, making it harder to link two files to the same phone.
• Batch cleaning: clean a whole set in one go.

HONEST LIMITS
A clean copy still looks like it was encoded on an iPhone. Reverse-image search can still match the picture. Device unlinking reduces the link to your phone; it can't remove it. A visible mark can be cropped or covered. And the app can't change traces outside the file: the account you post from, your IP address, your AirDrop name, or posting the same file twice.

Only clean content you own or have the right to share.

SUBSCRIPTION
Untraceable Pro is an auto-renewing subscription, monthly or yearly. Payment is charged to your Apple Account at confirmation of purchase. The subscription renews automatically unless auto-renew is turned off at least 24 hours before the end of the current period; renewal is charged within 24 hours before the period ends. Manage or cancel in your Apple Account settings. Any unused part of a free trial ends when you buy a subscription.

Terms of Use: https://www.apple.com/legal/internet-services/itunes/dev/stdeula/
Privacy Policy: https://namtran1985vn.github.io/Untraceable-Site/privacy/

## Subscriptions

| Field | Yearly | Monthly |
|---|---|---|
| Subscription group | Untraceable Pro | Untraceable Pro |
| Product ID | `untraceable.pro.annual` | `untraceable.pro.monthly` |
| Reference name | Pro Annual | Pro Monthly |
| Display name | Untraceable Pro Yearly | Untraceable Pro Monthly |
| Description (45) | Mark per buyer, unlinking and batch cleaning | Mark per buyer, unlinking and batch cleaning |
| Intro offer | Free trial *[length to decide]* | — |
| Price | *[to decide]* | *[to decide]* |

Each subscription also needs a review screenshot of the paywall, taken from a build that loads the products.

## App Privacy

- **Data collection:** "No, we do not collect data from this app." The label shows **Data Not Collected**.
- **Tracking:** none. No App Tracking Transparency prompt.
- Matches `PrivacyInfo.xcprivacy` in the app: no tracking, no collected data, required-reason APIs for UserDefaults (CA92.1) and file timestamps (C617.1).

## Export compliance

The app uses only encryption provided by iOS. `ITSAppUsesNonExemptEncryption` is `NO` in the build, so no question is asked per build.

## App Review notes

> Untraceable makes a clean copy of a photo or video on the device. There is no account or login, and the app makes no network requests of its own.
>
> To test: tap "Choose photos & videos", pick any photo, tap "Clean 1 item", then "See results". The report lists what was removed; "Share clean copy" and "Save to Photos" are available. Save to Photos asks only for add-only access.
>
> Pro features (per-buyer mark, device unlinking, batch) are behind the auto-renewing subscription and can be bought with a sandbox account. "Trace a leak" on the home screen looks up a code from the per-buyer mark; codes are random and the recipient list stays on the device.
>
> The app does not change what the picture shows, apart from the optional visible mark.

## Screenshots

`app-store/screenshots/` holds 6.9-inch iPhone screenshots (1320 × 2868), taken on the iPhone 17 Pro Max simulator with the status bar set to 9:41. App Store Connect scales them for smaller iPhones. Order:

1. `6.9in-1-home.png` — home
2. `6.9in-2-review.png` — ready to clean, per-buyer mark on
3. `6.9in-3-cleaning.png` — three of three verified clean
4. `6.9in-4-results.png` — what was found and removed
5. `6.9in-5-trace.png` — trace a leak

Sample media is the app's own illustrations; no real photos or people.
