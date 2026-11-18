---
layout: page
title: "Privacy Policy: Blurred Screen Share"
permalink: /private-screenshare/privacy/
---

_Last updated: 6 November 2026_

Blurred Screen Share does not collect, store, send or sell any personal data.

## What the extension does with your screen

When a website starts a screen share, for example Google Meet, the extension processes the video of your screen inside your own browser. It blurs the whole picture and passes only that blurred video to the website. No frame of your screen, blurred or not, is sent to the developer or to any server the developer runs. The blurred video goes only where the website would have sent your screen share anyway.

## What is stored

The extension saves two settings: whether blurring is on and the blur strength. They are saved with Chrome's `storage.sync` API. If you have Chrome sync turned on, Google syncs them between your own browsers. They contain nothing about you or your screen.

## Permissions

- **storage**: saves the two settings above.
- **Access to all websites**: any website can start a screen share, and the blur has to be in place before it does. So the extension runs a small script on every page. That script does nothing until the page asks to share your screen. It does not read page content, track browsing or send anything anywhere.

## Analytics and third parties

There is no analytics, tracking, advertising or remote code. The extension makes no network requests of its own.

## Contact

Questions or problems: open an issue at https://github.com/ahmednofal/private-screenshare/issues
