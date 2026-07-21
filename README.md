# The SMS & RCS Field Guide

A public pattern library for CleverTap messaging: **75 SMS** and **120 RCS** campaign use cases across **15 APAC verticals**. Each card gives the message, the trigger that makes it land, per-market compliance and RCS availability, and how to build it in CleverTap.

**Live:** https://shijunneo-bot.github.io/ct-sms-field-guide/

## What's inside
- **Two channels, one tool.** Switch between an **SMS** tab (75 patterns, 12 verticals) and an **RCS** tab (120 patterns, 15 verticals) at the top.
- **SMS vs WhatsApp vs RCS comparison** so you can pick the right channel in a call.
- **RCS feature guide** covering the three CleverTap template types (Text, Rich Card, Carousel), the three button types, limits and common misreads.
- **RCS availability across APAC (2026)** with an honest live vs not-yet market split and an SMS-fallback flag on every card.
- **Real CleverTap case studies** cited per vertical (Bandhan AMC anchors the RCS story with an 8-10% conversion uplift and 75% cost cut).
- **Filter and search:** by vertical, template type, job and pattern, grouped flat, by vertical, or by template. Click any card for the full brief and a mockup.

## The gallery network
Part of a 12-gallery CleverTap channel suite (AMP Email, Rich Push, SMS & RCS, WhatsApp, Linked Content, Recommendations & Catalog, Geofence, Reminders, Promos, Native Display, Product Experiences, Custom HTML In-App). Every page links to the full set via the top switcher and footer.

## Files
- `index.html` — the gallery (single self-contained file, no external assets beyond fonts).
- `og-image.png` — social share preview (1200x630).
- `robots.txt`, `sitemap.xml`, `llms.txt` — search and AI-engine discovery.
- `README.md` — this file.

## Deploy (GitHub Pages)
1. Upload all files in this folder to the repository root, replacing `index.html`.
2. Settings > Pages > Deploy from branch > `main` / root.
3. The page goes live at the URL above; updates are a same-name re-upload.

## A note on accuracy
This is a **directional reference**, not a guarantee. Verify sender-ID registration, consent, and carrier/RCS availability before any send. RCS renders only where the device and carrier support it and falls back to SMS elsewhere. RCS Business Messaging is not end-to-end encrypted, so keep OTPs and high-sensitivity content on an encrypted channel. Customer metrics are quoted from CleverTap's public case study library.
