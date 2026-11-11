# Review Poster Maker

A free tool for small businesses to collect more Google reviews. Enter your business name and Google review link, and get:

- **A review link** you can test and share
- **A printable QR code poster** in English, Tamil, or both
- **A ready-to-send WhatsApp message** for your customers

Made for local shops, restaurants, salons, clinics and service businesses in Tamil Nadu.

**Live site:** https://sriraaj23.github.io/review-poster-maker/

---

## Features

- QR code poster in A4 proportions, ready to print at A4 or A5
- Poster text in English, Tamil, or both languages
- Two business types: **Eatery** and **Shop or service**, each with its own wording
- Four poster colours
- Accepts a full Google review link or a Google **Place ID**
- Checks the pasted link and warns when it is not a Google link or is only a Maps location link
- Copy buttons for the link and the WhatsApp message, plus an **Open in WhatsApp** shortcut
- Works on phones and computers, in light and dark mode
- Remembers your details on your own device for next time

## How to use

1. Open the [live site](https://YOUR-USERNAME.github.io/review-poster-maker/).
2. Type your business name exactly as it appears on your signboard.
3. Paste your Google review link (see below).
4. Choose the language and colour.
5. Click **Save poster**, print it, and keep it near your billing counter.
6. Copy the WhatsApp message and send it to customers after their visit.

### Where to find your Google review link

1. Sign in to the Google account that owns your Business Profile.
2. Search for your business name on Google. Your profile controls appear above the results.
3. Choose **Ask for reviews** and copy the link.

No access to the profile? Use Google's [Place ID Finder](https://developers.google.com/maps/documentation/places/web-service/place-id) and paste the Place ID instead.

## Privacy

Everything runs in your browser. Nothing you type is sent to any server. Your details are saved only in your own browser's storage so the form is filled in next time.

## Review rules

Ask every customer for a review, not only the happy ones. Do not offer discounts, gifts or payment for reviews, and never post fake reviews. Google can remove reviews or suspend a Business Profile for breaking its policies.

## Technical details

- A single `index.html` file: plain HTML, CSS and JavaScript, no build step
- The poster is drawn on an HTML `<canvas>` at 1240 × 1754 px (A4 ratio)
- QR codes are generated with [qrcode-generator](https://github.com/kazuhikoarase/qrcode-generator) (MIT), included inside the file so the tool works without third-party servers
- Fonts: [Anek Tamil](https://fonts.google.com/specimen/Anek+Tamil) and [Hind Madurai](https://fonts.google.com/specimen/Hind+Madurai) from Google Fonts, with system font fallbacks

### Run it locally

Download `index.html` and open it in any modern browser. No installation needed.

### Publish your own copy

1. Fork this repository, or upload `index.html` to a new public repository.
2. Go to **Settings → Pages**.
3. Set Source to **Deploy from a branch**, choose `main` and `/ (root)`, and save.
4. Your site will be live at `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/` within a few minutes.

## Roadmap

- [ ] Upload a shop logo to show on the poster
- [ ] Table tent card and counter sticker sizes
- [ ] Review reply templates in English and Tamil
- [ ] Google Business Profile description writer
- [ ] Installable app (add to home screen)

## Contact

Need help setting up your Google Business Profile? Contact: _add your details here_

## License

This project is released under the [MIT License](LICENSE).

The QR code library is © 2009 Kazuhiko Arase, MIT License. See [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

---

This tool is not affiliated with, endorsed by, or sponsored by Google. Google and Google Maps are trademarks of Google LLC. QR Code is a registered trademark of DENSO WAVE INCORPORATED.
