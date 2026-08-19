# Tri-County Cyclones — Club Site

Newsletter, schedule, and volunteer signups for the Tri-County Cyclones youth hockey program.

- **Frontend:** static single-page app (`index.html`), deployable anywhere (Netlify / GitHub Pages)
- **Backend:** Supabase project `kent-cyclones` — `events` and `signups` tables via the REST API
- **Volunteer roles:** Penalty Box (every game), Scoreboard + Music (home games only), custom roles for events
- **Admin:** "Manage schedule" link at the bottom of the Schedule tab (PIN in `index.html`, `ADMIN_PIN`)

## Updating the newsletter

Newsletter content is the News tab in `index.html`. Edit and push — the site redeploys automatically.

## Notes

- Signups are trust-based: anyone with the link can claim or free a spot.
- Double-booking is prevented by a unique constraint in the database.
