# RSVP Buddy — website

Static website for **RSVP Buddy**, a free, read-only iPhone companion to the
Calendar app (iOS 17+). Served with GitHub Pages from the `main` branch root.

## Pages

| Page | URL |
|---|---|
| Home | https://forszpanen.github.io/public-rsvp-buddy-ios/ |
| Privacy policy | https://forszpanen.github.io/public-rsvp-buddy-ios/privacy/ |
| Support | https://forszpanen.github.io/public-rsvp-buddy-ios/support/ |
| Press kit | https://forszpanen.github.io/public-rsvp-buddy-ios/press/ |
| Not found | `404.html` (served by GitHub Pages for missing paths) |

## How it is made

Plain HTML and one stylesheet (`assets/site.css`). No JavaScript, no external
fonts or CDNs, no analytics, no cookies — the site makes no requests outside
itself, in line with the app's privacy policy.

The content is generated from the `appstore/` folder of the private app
repository: the privacy and support text are converted from
`appstore/privacy-policy.md` and `appstore/support.md` without changes in
meaning, the landing-page copy is a shortened version of the English App Store
description in `appstore/listing.md`, and the screenshots, videos and
illustrations are copied unmodified. Video posters (`assets/video/*-poster.jpg`)
are single frames taken 1.5 s into each video; the favicon and Apple touch icon
are resized from the 1024 px app icon.

When the privacy policy or support text changes in the app repository, update
the matching page here and the "Last updated" date.

All links are relative, so the site works under the `/public-rsvp-buddy-ios/`
project path. The only exception is `404.html`, which uses absolute URLs
because GitHub Pages serves it at whatever path was requested.

## License

Text and media © 2026 RSVP Buddy. Press, reviewers and bloggers may use the
files in `assets/` to write about RSVP Buddy; all other rights reserved. The
repository is public so that GitHub Pages can serve it.

Contact: rsvpbuddy.app@icloud.com
