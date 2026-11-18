---
title: Support
description: Help with Untraceable – cleaning photos and videos, Pro, the per-buyer mark, and getting in touch.
permalink: /support/
---

# Support

<p class="updated">Untraceable – for Creators</p>

<div class="note" markdown="1">
**Contact:** {% if site.support_email != "" %}email [{{ site.support_email }}](mailto:{{ site.support_email }}). We usually reply within two working days.{% else %}open an issue at [{{ site.issues_url | remove: "https://" }}]({{ site.issues_url }}). Issues are public, so never attach a photo, video or personal details.{% endif %}
</div>

## Getting started

### What does the app remove?
Location and capture time, phone model, lens and serial numbers, owner names and captions, editing data and linking IDs, embedded previews and depth data, and extra video tracks such as subtitles or location tracks. The file gets a neutral name and its dates are reset. The [home page]({{ '/' | relative_url }}#removed) has the full list.

### Which files can I clean?
Photos in **JPEG, HEIC and PNG**, and videos in **MOV and MP4**. Other files (for example GIFs) show as "Not supported" and are never passed through. A damaged file that can't be read in full is refused rather than repaired.

### Why is my clean photo a JPEG?
JPEG opens everywhere. A HEIC photo comes out as a JPEG and can be a little larger; a PNG stays a PNG. Videos come out as MP4 with one picture track and one sound track.

### Does the app change my picture or sound?
No. The picture and sound are re-encoded, which loses a tiny amount of quality, but nothing is covered, blurred or edited. The only visible change is the per-buyer mark, and only if you turn it on.

### Do I need to keep the app open?
Yes, while it is cleaning. Short items take seconds; a long 4K video takes longer. If you leave the app, iOS gives it a short time to finish, then the current item is cancelled cleanly and you can clean it again.

### Where are my originals?
Your originals stay where they were, in Photos or Files. The app works on its own copies, deletes them once each clean copy passes its check, and deletes the clean copies when you tap **Done**.

## Untraceable Pro

### What's free and what's Pro?
Cleaning one item at a time is free, with every removal included. Pro adds the per-buyer mark and leak lookup, device unlinking, and batch cleaning.

### How do I cancel?
On your iPhone, open **Settings › [your name] › Subscriptions**, choose Untraceable and tap **Cancel Subscription**. You keep Pro until the end of the period you paid for.

### I bought Pro but it isn't active
Open the app's **Settings** and tap **Restore purchases**. Make sure you're signed in with the Apple Account you bought it with. For refunds, use [Apple's report a problem page](https://reportaproblem.apple.com).

## Per-buyer mark

### How does tracing a leak work?
Turn on **Per-buyer mark**, choose or add a recipient, and clean. A random five-character code (like `7QX-4M`) is tiled across the picture. If a copy turns up somewhere it shouldn't, open **Trace a leak** and type the code to see who it was made for.

### Where is the recipient list kept?
Only on your iPhone, and in your iPhone's own backup. If you delete the app without a backup, the list is gone and old codes can no longer be looked up.

### Can someone remove the mark?
A determined person can crop or cover a visible mark. It deters casual leaks and helps trace them; it can't stop every leak.

## Limits

A clean copy still looks like it was encoded on an iPhone, reverse-image search can still match the picture, and device unlinking reduces the link to your phone without removing it. The app can't change traces outside the file: the account you post from, your IP address, your AirDrop name, or posting one file in two places.

## Privacy

The app collects nothing and sends nothing. Read the [Privacy Policy]({{ '/privacy/' | relative_url }}) and the [Terms of Use]({{ '/terms/' | relative_url }}).
