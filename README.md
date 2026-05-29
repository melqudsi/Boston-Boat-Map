# Boston Boat Map

Static, mobile-friendly Leaflet map for Boston Electric Boats route planning.

## Features

- Separate scenic route views for Romantic, Greatest Hits, History, and Show All.
- Boston Electric Boats FAQ-safe boundary reminders, including no Charles River locks and the Hyatt Logan / Legal Harborside outer-harbor line.
- North-side advisory reminders for the Tobin / Mystic / Encore direction.
- Mobile-friendly collapsible route panel.
- One locate button that enables GPS, follow/center mode, and compass/heading when the browser allows it.
- Barrier proximity warnings: when your current GPS location is within about 175 meters of a marked barrier/advisory line, the nearest barrier glows red and a warning icon appears.

## GitHub Pages deploy

1. Put `index.html` in the root of this repo.
2. In GitHub, go to **Settings → Pages**.
3. Set **Source** to **Deploy from a branch**.
4. Choose branch **main** and folder **/** root.
5. Save. The app will publish at `https://melqudsi.github.io/Boston-Boat-Map/` after GitHub Pages builds.

## Notes

This is a planning aid, not marine navigation. Follow Boston Electric Boats' onboard guide map/navigation and crew instructions. GPS and compass require HTTPS, device permissions, and compatible mobile browser support.
