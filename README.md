# munajat-site

Marketing website for [Munajat — Dhikr & Dua](https://github.com/TrabelsiAchraf/Munajat), a privacy-first iOS app for daily adhkar.

Hosted via GitHub Pages from this repository's `main` branch root.

Live URLs:

- Home: <https://trabelsiachraf.github.io/munajat-site/>
- Support: <https://trabelsiachraf.github.io/munajat-site/support.html>
- Privacy: <https://trabelsiachraf.github.io/munajat-site/privacy.html>
- Accessibility: <https://trabelsiachraf.github.io/munajat-site/accessibility.html>

## Local preview

Pure static HTML — open `index.html` in a browser, or serve with any static server:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Updating screenshots

The marketing images come from the Munajat repo (`marketing/raw/en/` for the in-app captures and `marketing/out/en/01_home.png` for the styled hero). Replace `hero.png` / `shot-1.png` … `shot-4.png` as the app evolves.

## Updating the App Store link

Once the app is approved, replace every `<a href="#">` pointing to the App Store CTA in `index.html` (search for `Coming soon on the App Store`).
