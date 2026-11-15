# Blessed Menorah: Official Profile Website

One-page profile site for **Blessing Unekuojo Oguche**, known as **Blessed Menorah**, a Nigerian gospel singer and worship minister based in Sheffield, UK. She won Best Female Singer (Diaspora) at the 2025 Eko Heritage Awards.

## What's here

- `index.html`: the whole website (styles, animation and scripts in one file)
- `Images/`: photos used on the site, named `blessed-menorah-NN-event-description.jpg`

## Editing content

Open `index.html` and find the `PROFILE` block near the top of the `<script>`. Everything is edited there:

- `links`: YouTube, Instagram, TikTok and featured video URLs
- `bookingEmail` / `bookingPhone`: where booking requests go
- `theme`: `"gold"`, `"aurora"`, `"sunset"`, `"forest"` or `"noir"`; set `hideThemePicker: true` to remove the colour switcher
- `highlights`, `awards`, `videos`, `gallery`, `organisations`: the cards in each section

To add a photo, put it in `Images/` and add it to `gallery` (or set it as a highlight's `img`).

## Hosting

The site is ready for GitHub Pages: **Settings → Pages → Deploy from branch → `main` / root**.
