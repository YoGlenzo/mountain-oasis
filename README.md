# Mountain Oasis website

The website for Mountain Oasis, 47 Theresa Avenue, Camps Bay, Cape Town.

These are plain web pages: there is nothing to install and no build step.

## Pages

| File | What it is |
|---|---|
| `index.html` | Homepage: gallery, reviews, listings, Book Now buttons and chat assistant |
| `camps-bay-guide.html` | Guest guide to Camps Bay |
| `checkin-tour.html` | Check-in tour (upstairs) |
| `checkin-tour-downstairs.html` | Check-in tour (downstairs) |
| `checkin-tour-wholehouse.html` | Check-in tour (full house) |
| `skygate-competition.html` | A copy of the homepage made for a competition |

## Photos

- `images/` holds the homepage and competition photos. Some (`photo-01` to `photo-13` and `Screenshot 2026-08-24…`) are kept for later use and aren't on any page yet.
- The `Screenshot 2026-05-*.png` files and `ChatGPT Image May 19, 2026….png` in the top folder are the check-in tour photos. The tour pages expect them there, so don't move them.

## Publishing

Every change on the `main` branch is published automatically with GitHub Pages by
`.github/workflows/deploy-pages.yml`. Progress shows under the **Actions** tab.

To turn this on for a new copy of the repository: **Settings → Pages → Source: GitHub Actions**.
The custom domain is set on that same page. `CNAME` records the domain the site used before
(`mountain.co.za`). A domain can only be attached to one GitHub Pages site at a time, so remove it
from the old site before adding it here.

## Outside services

- **Airbnb:** the Book Now buttons and listing cards link to the four Airbnb listings.
- **Formspree** (form `mrejjrbo`): the check-in tour forms. Messages go to whoever owns that Formspree account.
- **Behold.so:** the Instagram feed on the homepage.
- **Google Fonts and Google Maps:** no account needed.
