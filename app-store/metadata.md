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

See what a photo gives away, then make a clean copy on your iPhone. Mark each buyer's copy with their own code, discreet or strong, and know who leaked it.

## Keywords (100)

metadata,exif,remover,gps,location,privacy,strip,geotag,watermark,leak,trace,serial,scrub,share

## Description (4000)

Share the picture, not what's hidden in the file.

Check a photo or video first and see what it gives away, with the actual values: where it was taken, which phone, the time, a name. Then make a clean copy.

Phones and editing apps write details into every photo and video: where it was taken, which phone and lens, serial numbers, the date and time, your name, and extra tracks inside videos. Untraceable makes a clean copy before you post or send it. Everything runs on your iPhone. The picture and sound stay the same. Unlike a screenshot, the copy is full quality, and it works on video.

Files sent by email, by link or as a document arrive unchanged, with everything inside them. A clean copy has nothing hidden to carry.

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
• Per-buyer mark: pick one clip and tick who it's for. Each recipient gets their own copy with their own random code. A recipient can be one buyer or a list of buyers. Choose how much the code shows: discreet, standard or strong. If a copy leaks, type the code to see who it was made for.
• Proof card and leaker flag: a matched code gives you a card to screenshot for a report, and a flag that warns you before you make that person another copy.
• Batch cleaning: clean a whole set in one go.
• A locked recipient list: it stays on your iPhone and opens with Face ID or your passcode.
• Device unlinking: normalises size and softens sensor noise. In our lab test this made a phone's sensor pattern about three times weaker; a phone can still be matched.

HONEST LIMITS
A clean copy still looks like it was encoded on an iPhone. Reverse-image search can still match the picture, a background can be matched to other photos of the same place, and face search can find you in other photos. Device unlinking reduces the link to your phone; it can't remove it. A visible mark can be cropped or covered, and its code shows who received a copy, not who posted it. And the app can't change traces outside the file: the account you post from, names on payments and wish lists, posting while you're still at a place, posting the same file twice, your IP address, or your AirDrop name.

Only clean content you own or have the right to share.

SUBSCRIPTION
Untraceable Pro is an auto-renewing subscription, monthly or yearly, each with a one-week free trial. Payment is charged to your Apple Account at confirmation of purchase. A free trial turns into a paid subscription when it ends unless you cancel at least 24 hours before. The subscription renews automatically unless auto-renew is turned off at least 24 hours before the end of the current period; renewal is charged within 24 hours before the period ends. Manage or cancel in your Apple Account settings. Any unused part of a free trial ends when you buy a subscription.

Terms of Use: https://www.apple.com/legal/internet-services/itunes/dev/stdeula/
Privacy Policy: https://namtran1985vn.github.io/Untraceable-Site/privacy/

## Subscriptions

| Field | Yearly | Monthly |
|---|---|---|
| Subscription group | Untraceable Pro | Untraceable Pro |
| Product ID | `untraceable.pro.annual` | `untraceable.pro.monthly` |
| Reference name | Pro Annual | Pro Monthly |
| Display name | Untraceable Pro Yearly | Untraceable Pro Monthly |
| Description (45) | Per-buyer marks, batch cleaning, unlinking | Per-buyer marks, batch cleaning, unlinking |
| Intro offer | One-week free trial | One-week free trial |
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
> To test: on the home screen tap "Check a photo or video" and pick any photo: the screen lists what the file gives away. Tap "Make a clean copy"; Results opens on its own with what was removed. "Share clean copy" and "Save to Photos" are available; Save to Photos asks only for add-only access. "Clean photos & videos" does the same for one item, or many with Pro.
>
> Pro (per-buyer mark, batch, device unlinking) is an auto-renewing subscription with a one-week free trial; use a sandbox account. With Pro, turn on "Per-buyer mark" on the Review screen, add a recipient, pick a style and clean: each copy carries its own random code. "Trace a leak" on the home screen looks up a code. The recipient list stays on the device and opens with Face ID or the passcode; on a device without a passcode it opens directly.
>
> The app does not change what the picture shows, apart from the optional visible mark and an optional small dot (Settings).

## Screenshots

`app-store/screenshots/` holds 6.9-inch iPhone screenshots (1320 × 2868), taken on the iPhone 17 Pro Max simulator with the status bar set to 9:41, from build 1.0 (1). App Store Connect scales them for smaller iPhones. Order:

1. `6.9in-1-home.png` — home: check a file, clean, per-buyer mark, trace a leak
2. `6.9in-2-check.png` — what a photo gives away, with the actual values
3. `6.9in-3-review.png` — per-buyer mark for three recipients, Discreet style
4. `6.9in-4-results.png` — clean copies ready, one marked copy per recipient
5. `6.9in-5-recipients.png` — recipients: a username and two lists
6. `6.9in-6-trace-match.png` — trace a leak: match found
7. `6.9in-7-proof-card.png` — proof card to screenshot for a report

Sample media is the app's own illustrations; the location and the name "Mai Nguyen" on the Check screen are planted test values, not a real person.
