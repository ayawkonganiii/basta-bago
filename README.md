# HabalGo (demo build)
Open index.html in a browser (or deploy the folder to Vercel/Netlify as a static site).
Data is stored in localStorage (this browser only). It is NOT a shared database.
Demo steps: login page > Admin > First-time admin setup, then register a rider, approve as admin, set Available, book as passenger.
Production: replace the DB object/save() in js/app.js with Supabase (auth, tables, storage, row-level security).
