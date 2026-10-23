# India Sports & Recreation Facilities

Searchable directory of 2,130 sports & recreation facilities across all 36 Indian
states/UTs — football turfs, cricket grounds, swimming pools, boxing academies,
archery ranges, horse-riding centres, kayaking spots and government multi-sport venues.

Live: served via GitHub Pages from this repository (static site; the browser filters
`data/facilities.json`).

## Structure
- `index.html`          the app (search, filters, pagination)
- `data/facilities.json` full dataset
- `netlify/`            optional serverless API version (see the bundled zip)

## Data note
Compiled from publicly listed sources (operator sites, booking platforms, official
sports bodies). Not an official government dataset. Fields like village, panchayat,
usage_fee and pool_depth are "Not stated" where operators don't publish them.
