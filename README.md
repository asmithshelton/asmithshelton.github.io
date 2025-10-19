# SQLime + TravelAgencyDB (Ready to Upload)

This folder contains:
- `TravelAgencyDB.sqlite` — a SQLite database with 5 tables + sample data
- `index.html` — quick instructions and demo queries
- `.nojekyll` — for GitHub Pages (so files like `.sqlite` are served)

## Host this folder
Upload everything to your static host (any of these work):
- GitHub Pages (recommended)
- NVCC faculty web space
- Netlify / Vercel

## Share with students
1. Publish this folder so `TravelAgencyDB.sqlite` is publicly reachable.
2. Tell students to go to **https://sqlime.org/** → **Open → From URL** → paste the URL to `TravelAgencyDB.sqlite`.

### Optional quick link
If your host allows cross-origin fetch, you can prefill the DB by linking:
```
https://sqlime.org/#YOUR_PUBLIC_DB_URL
```
(Replace `YOUR_PUBLIC_DB_URL` with your actual URL to the `.sqlite` file.)

## Tables in the DB
- Travelers (10 rows)
- Destinations (10 rows)
- Tours (10 rows)
- Bookings (10 rows)
- Payments (10 rows)
- View: `v_BookingTotals`

## Demo queries
See `index.html` for copy/paste queries (JOINs, aggregates).

## Notes
- All data is synthetic and safe for classroom use.
- If `#URL` preloading doesn't work on your host, students can always use **Open → From URL** inside SQLime.
