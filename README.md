# The SMS Field Guide

An interactive pattern library for the CleverTap SMS add-on. 75 use cases across 12 APAC verticals, each with a sample message, the trigger that makes it relevant, the market's deliverability rules, and how to build it in CleverTap.

**Live site:** https://shijunneo-bot.github.io/ct-sms-field-guide/

---

## What it is

A single-page reference for teams deciding what to send over SMS and how to ship it. It is organised around the jobs SMS is genuinely good at, not a dump of templates. Every card pairs the message with the signal that makes it land and whether it will deliver in a given market, so you can move from a pattern to a live campaign without guessing.

## What's inside

- **75 use-case cards** across 12 APAC verticals, colour-coded by vertical.
- **7 SMS jobs** the channel wins at: reachability floor, no-app reach, time-critical transactional, renewal and expiry, mass ops reach, compliance-grade alert, and transactional cross-sell.
- **A phone mockup** on every card with the sample message, plus a copy button that grabs the exact text with the prefix, opt-out, placeholder, and emoji intact.
- **The full brief per card:** goal and roadblock, mechanics, the timing signal, a "Why SMS, not WhatsApp" call, the market compliance flags, and a "Set up in CleverTap" hint that names the right qualification type for that card's pattern.
- **Market compliance flags** for APAC (Singapore, Malaysia, India, the Philippines and more): registered Sender ID, link and URL rules, template requirements, and free-message prefixes.
- **Search, filter, and group** by vertical, SMS job, or message pattern.
- **Two guides built in:** "How to use this gallery" and "Build it in CleverTap" (the five-step campaign flow, the provider prerequisite, personalisation tokens, and what you can layer on).
- **Mobile-ready:** single-column layout, collapsible filters, and a full-screen card view on small screens.

## Deploy

This is a single self-contained `index.html`. There is no build step and no assets folder.

1. Create a public GitHub repository.
2. Upload `index.html` and keep the name.
3. In **Settings, then Pages**, set the source to **Deploy from a branch**, branch **main**, folder **/ (root)**, and save.
4. The site goes live at `https://<username>.github.io/<repo>/` within about a minute.

## Run it locally

Open `index.html` in any modern browser. Everything is inline, so it works offline. Without a connection the fonts fall back to system fonts, and the copy button uses a local fallback when the page is opened straight from a file.

## How it is built

- One HTML file. The CSS and JavaScript are inline, and the card data lives in a small array in the page.
- No images. Badges are emoji, the phone and cards are HTML and CSS, and the icons are inline SVG.
- The favicon is embedded as a data URI. The web fonts load from Google Fonts.

## A note on the compliance data

The flags are a directional reference, not legal advice, and SMS regulations change. Confirm Sender ID registration, consent, and the current market rules before any send. SMS is orchestrated by CleverTap and delivered through your integrated provider, which owns final delivery, throughput, and cost.

## Companion galleries

- **Custom HTML In-App Template Gallery** — https://shijunneo-bot.github.io/ct-template-gallery/
- **AMP Email Template Gallery** — https://shijunneo-bot.github.io/amp-email-gallery/
