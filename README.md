# kivori-legal

Static site hosting Kivori's privacy policy and terms of service, published via GitHub Pages.

- Landing: `index.html`
- Privacy policy: `privacy.html` (bilingual: 日本語 / English)
- Terms of service: `terms.html` (bilingual: 日本語 / English)

The bilingual content is generated verbatim from the app's source of truth in
[`kazuki-0418/Kivori`](https://github.com/kazuki-0418/Kivori) at
`assets/legal/{privacy,terms}_{ja,en}.md`. To update, refresh those markdown files
in the app repo, re-convert to HTML, and update the corresponding sections here.

Logo: extracted from the app's iOS store icon
(`ios/Runner/Assets.xcassets/AppIcon.appiconset/Icon-App-1024x1024@1x.png`).
