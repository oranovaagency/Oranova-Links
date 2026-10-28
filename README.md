<p align="center">
  <img src="img/oranova-logo.svg" alt="Oranova" width="240">
</p>

<h1 align="center">Oranova</h1>

<p align="center">
  <strong>Websites, apps and ads for businesses.</strong>
</p>

<p align="center">
  <a href="https://oranovaagency.github.io/Oranova-Links/"><strong>Visit our links page</strong></a> ·
  <a href="https://instagram.com/oranova.agency">Instagram</a> ·
  <a href="https://tiktok.com/@oranova_agency">TikTok</a> ·
  <a href="mailto:oranovaagency31@gmail.com">Email</a>
</p>

---

## Who we are

**Oranova** is a digital agency born in **Oran, Algeria**. We help businesses get online, get found and get more customers with modern websites, apps, automation and smart advertising.

We started with the businesses around us, like restaurants, shops and car rentals in Oran, and we now work with clients in any country.

## The name

**Oranova** reads two ways:

- **Oran + nova**: a new star rising from Oran.
- **Ora nova**: Latin and Italian for *a new era*.

Both say the same thing. We bring local businesses into a new era.

Our logo shows it too. The open circle is Oran and the full range of services we offer, and the spark breaking out of it is the new era.

## What we do

| Service | What you get |
|---------|--------------|
| **Websites** | Fast, mobile-first sites that show up on Google and turn visitors into calls, bookings and orders. |
| **Mobile apps** | Android and iOS apps for ordering, booking, loyalty and more. |
| **Desktop software** | Custom tools for managing stock, sales, rentals and daily operations. |
| **Chatbots** | Assistants that answer customers on WhatsApp, Instagram and your website, day and night. |
| **Automations** | Workflows that remove repetitive work: orders, reminders, invoices, follow-ups. |
| **Ads and social media** | Content and paid campaigns on Instagram, TikTok and Facebook that bring real customers. |
| **QR menus** | Digital menus for restaurants and cafés, easy to update with no reprinting. |
| **NFC cards** | Smart business cards: one tap opens your page, contacts and socials. |

## How we work

- **We speak your language.** Darija, French, Arabic or English.
- **We show results, not jargon.** More orders, more calls, more bookings. Things you can measure.
- **We show the work.** Before and after, screen recordings, your real photos instead of stock images.
- **We build for the long run.** Simple to maintain and easy to update, with support when you need it.

## The team

Oranova's core team: **Mehdi**, **Migos**, **Lios** and **Said**.

## Contact

| Channel   | Link |
|-----------|------|
| Instagram | [@oranova.agency](https://instagram.com/oranova.agency) |
| TikTok    | [@oranova_agency](https://tiktok.com/@oranova_agency) |
| Facebook  | [Oranova](https://facebook.com/) |
| Email     | [oranovaagency31@gmail.com](mailto:oranovaagency31@gmail.com) |
| Links page | [oranovaagency.github.io/Oranova-Links](https://oranovaagency.github.io/Oranova-Links/) |

---

## About this repository

This repository hosts the **official Oranova links page**. It opens when someone taps an Oranova NFC card or scans its QR code, and gives them every way to reach us in one place.

### Features

- **WhatsApp chat** with a pre-written message
- **Email, Instagram, TikTok and Facebook** links
- **Services overview** of everything we offer
- **Save contact:** downloads a vCard straight to the phone
- **Share:** sends the page with the device's native share sheet
- **Bilingual:** French and Arabic, with a language switch
- **Lightweight:** a single HTML file, no build step, no dependencies

### Project structure

```
index.html   The whole page (HTML, CSS and JavaScript)
img/         Oranova logo and icon (SVG)
```

### Hosting

The page is hosted for free on **GitHub Pages**:
Settings → Pages → Source: *Deploy from a branch* → `main` / root.

> [!WARNING]
> The repository must keep the name `Oranova-Links`. Its address is printed in the QR code and programmed into the NFC chip of every Oranova card, so renaming the repository breaks every card in circulation.

### Updating

- **Phone / WhatsApp number:** edit the `PHONE` constant at the top of the `<script>` in `index.html`.
- **Texts:** the French and Arabic strings are in the `T` object in the same script.

Commit to `main` and GitHub Pages redeploys automatically within a minute or two.

---

<p align="center">
  <img src="img/oranova-icon.svg" alt="" width="32"><br>
  © 2026 Oranova · Oran, Algérie
</p>
