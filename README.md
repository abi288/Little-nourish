# Little Nourish Web Version

This is the simplest version of the baby feeding tracker.

## Run
Open `index.html` in a browser.

No server, database, account or paid service is required.

## Free online hosting
Upload `index.html` to any static hosting service such as GitHub Pages or Netlify.

## Included
- Baby name and current weight
- Editable 120–180 mL/kg/day multiplier, default 150
- Rolling 24-hour milk total
- Target, remaining amount and progress bar
- Add/edit/delete feeds
- Date and exact time
- Amount in mL
- Bottle, breastfeeding, formula, expressed milk, other
- Notes
- Feed history
- 7-day consumption chart
- Feed timing list
- CSV export
- Browser print / Save as PDF
- Mobile-first responsive design
- Local timezone display

## Important limitation
This version stores everything in the browser's localStorage. It does NOT provide real-time sharing between two parents.

For two-parent real-time syncing, a backend is required. The cheapest practical next step is to connect this same web app to a free-tier backend such as Supabase, with authentication and Row Level Security. The frontend can remain essentially the same.

The 150 mL/kg/day calculation is a tracking calculation, not medical advice.
