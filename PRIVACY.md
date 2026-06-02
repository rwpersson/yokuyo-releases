# Yokuyo — Privacy Policy

_Last updated: 2026-06-01_

Yokuyo (抑揚) is a Japanese pitch-accent visualization tool, available as a Windows
desktop application and a companion browser extension. This policy covers both.

## Summary

**Yokuyo does not collect, store, or transmit your personal data to us or to any third
party. There are no analytics, no tracking, no accounts, and no remote servers.**

## What the browser extension does

When you hold **Shift** and hover over Japanese text on a web page, the extension reads
the Japanese sentence under your cursor and sends it to the **Yokuyo desktop app running
locally on your own computer** (at `http://localhost`) so it can be analyzed and displayed.

- The hovered text is sent **only to the local Yokuyo app on your machine**. It never
  leaves your computer and is never sent to the developer or any external service.
- The extension makes **no network requests to remote servers**.
- The extension stores small, non-personal preferences in your browser's local storage:
  the panel size and the local address of the Yokuyo app. These never leave your device.

The extension requires a host permission for all websites (`<all_urls>`) for one reason
only: to detect Japanese text on the page you are reading so it can respond to Shift+hover.
It does not read, collect, or transmit page content for any other purpose.

## What the desktop app does

The desktop app analyzes Japanese text locally and synthesizes audio locally using the
VOICEVOX engine on your computer. Audio is generated on-device and is not uploaded or
redistributed. The app checks GitHub for software updates; this involves a standard
request to GitHub's servers and sends no personal data.

## Voice credits

Audio is synthesized with VOICEVOX. Voice credits:
`VOICEVOX:玄野武宏(CV:ガロ)` · `VOICEVOX:四国めたん` · `VOICEVOX:剣崎雌雄` · `VOICEVOX:あいえるたん`.

## Changes

If this policy changes, the updated version will be posted at this page.

## Contact

Questions: yokuyokoushiki@gmail.com
