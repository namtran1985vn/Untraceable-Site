---
title: Privacy Policy
description: "How Untraceable handles your photos, videos and data. Short version: everything stays on your iPhone and nothing is collected."
permalink: /privacy/
---

# Privacy Policy

<p class="updated">Untraceable – for Creators · Last updated 18 November 2026</p>

<div class="note" markdown="1">
**The short version:** Untraceable runs entirely on your iPhone. We do not collect, receive, store or sell any of your photos, videos or personal data. The app has no account, no server, no analytics, no ads and no third-party SDKs.
</div>

## What the app does with your files

When you choose a photo or video, Untraceable copies it into a private, protected folder inside the app. Only the app can read that folder, and it is excluded from device backups. The app then:

1. reads the file to list what hidden data it contains (for example location or phone model). It keeps only the *kind* of data found, never the values;
2. writes a new, clean copy from the picture and sound alone;
3. opens the clean copy again and checks it. A copy that fails the check is deleted.

The original is deleted from the app as soon as its clean copy passes the check. Clean copies are deleted when you tap **Done**, when you start a new batch, or the next time the app starts. Nothing is uploaded at any point.

## Data we collect

**None.** We do not collect any data from the app, and the app sends nothing to us or to anyone else. In App Store terms, the app's privacy label is **Data Not Collected**.

## Data stored on your iPhone

| What | Where | How long |
|---|---|---|
| Photos and videos you choose, and their clean copies | A private folder inside the app, excluded from backups | Until the session ends (see above) |
| The per-buyer recipient list (names or notes you type, the random codes, and how many copies were marked) | Inside the app, protected with iOS file encryption | Until you delete the app. It is included in your iPhone's own backup (for example iCloud Backup, if you use it), so a leak can still be traced after you restore a phone. Apple handles that backup; we never receive it |
| A note that you finished the first-run screen | The app's settings on your iPhone | Until you delete the app |

## Permissions

- **Choosing photos and videos:** the app uses Apple's system photo picker and the Files app. It does not ask for access to your photo library and cannot see anything you don't pick.
- **Save to Photos:** when you tap Save to Photos, iOS asks for permission to **add** items. The app can add clean copies but cannot read your library. Saved copies carry no location.
- The app does not use the camera, microphone, location, contacts, tracking or notifications.

## Purchases

Untraceable Pro is bought through the App Store. Apple processes the payment; we never see your payment details or your Apple Account. The app asks the App Store whether you have an active subscription, and that request goes from your iPhone to Apple under [Apple's privacy policy](https://www.apple.com/legal/privacy/).

## Network

The app makes no network requests of its own. The only connections are those iOS makes to Apple for the App Store and subscriptions.

## This website

This site is hosted on GitHub Pages. It uses no cookies, analytics, ads or third-party embeds, and every image is served from this site. GitHub may record technical information such as your IP address when you visit, as described in [GitHub's privacy statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).

## Children

Untraceable is not directed at children under 13, and we do not knowingly collect information from anyone, including children.

## Your choices

Everything the app keeps is on your device. You can remove all of it by deleting the app. Clean copies you shared or saved to Photos are yours to manage in those places.

## Changes

If this policy changes, the new version will be posted on this page with a new date. If the app ever starts collecting data, this policy and the App Store privacy label will be updated before that version is released.

## Contact

Questions about privacy: {% if site.support_email != "" %}[{{ site.support_email }}](mailto:{{ site.support_email }}){% else %}see the [support page]({{ '/support/' | relative_url }}){% endif %}.
