# Dashboard Daerah Seberang Perai Tengah - Web Upgrade

This version corrects the geography by using Daerah Seberang Perai Tengah as the main dashboard area, while keeping P.045 Bukit Mertajam as the focus area.

## How to deploy on Netlify
1. Unzip this folder.
2. Go to https://app.netlify.com/drop
3. Drag the folder `spt-web-upgrade` into Netlify Drop.
4. Rename the Netlify site if desired.

## Data logic
- Population card fetches live CSV from OpenDOSM/data.gov.my: https://storage.dosm.gov.my/population/population_district.csv
- Map uses OpenStreetMap tiles and Leaflet.
- Charts are editable in `app.js`.

## Geography note
Bukit Mertajam is not an administrative district. Use:
- Main geography: Daerah Seberang Perai Tengah
- Focus geography: P.045 Bukit Mertajam
- DUN: N.13 Berapit, N.14 Machang Bubuk, N.15 Padang Lalang
