<p align="center">
  <img src="img/oranova-logo.svg" alt="Oranova" width="220">
</p>

<h1 align="center">Oranova · Links</h1>

<p align="center">
  <strong>AI, websites and ads for businesses.</strong><br>
  <em>Votre business, à l'ère de l'IA.</em>
</p>

<p align="center">
  <a href="https://oranovaagency.github.io/Oranova-Links/">Live page</a> ·
  <a href="https://instagram.com/oranova.agency">Instagram</a> ·
  <a href="mailto:oranovaagency31@gmail.com">Email</a>
</p>

---

## About

**Oranova** is a digital agency based in Oran, Algeria. We build websites, mobile apps, desktop software, QR menus and NFC cards, and we help local businesses move into the era of AI.

This repository hosts our official links page. It opens when someone taps an Oranova NFC card or scans its QR code, and gives them every way to reach us in one place.

## Features

- **WhatsApp chat** with a pre-written message
- **Email, Instagram, TikTok and Facebook** links
- **Services overview:** websites, mobile apps, desktop software, QR menus and NFC cards
- **Save contact:** downloads a vCard straight to the phone
- **Share:** sends the page with the device's native share sheet
- **Bilingual:** French and Arabic, with a language switch
- **Lightweight:** a single HTML file, no build step, no dependencies

## Contact

| Channel   | Link |
|-----------|------|
| Instagram | [@oranova.agency](https://instagram.com/oranova.agency) |
| TikTok    | [@oranova_agency](https://tiktok.com/@oranova_agency) |
| Facebook  | [Oranova](https://facebook.com/) |
| Email     | [oranovaagency31@gmail.com](mailto:oranovaagency31@gmail.com) |

## Project structure

```
index.html   The whole page (HTML, CSS and JavaScript)
img/         Oranova logo and icon (SVG)
```

## Hosting

The page is hosted for free on **GitHub Pages**:
Settings → Pages → Source: *Deploy from a branch* → `main` / root.

> [!WARNING]
> The repository must keep the name `Oranova-Links`. Its address is printed in the QR code and programmed into the NFC chip of every Oranova card, so renaming the repository breaks every card in circulation.

## Updating

- **Phone / WhatsApp number:** edit the `PHONE` constant at the top of the `<script>` in `index.html`.
- **Texts:** the French and Arabic strings are in the `T` object in the same script.

Commit to `main` and GitHub Pages redeploys automatically within a minute or two.

---

<p align="center">© 2026 Oranova · Oran, Algérie</p>
