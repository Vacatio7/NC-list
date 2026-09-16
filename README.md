# NC Material E-Paper

Mobile web prototype for recording non-conforming material.

## Prototype login
- Users: `admin`, `user1`–`user5`
- Password: `1234`

## Current functions
- Mobile-friendly login
- Automatic current date/time and reporter
- Material search by Part No. or Part Name
- Approved-BOM validation; invalid material cannot be submitted
- NC quantity, reason and remarks
- Records view
- Admin-only material master view

## Important prototype limitation
Records are currently stored in browser `localStorage`. They are therefore not shared between different phones/browsers. Production deployment needs server-side authentication and a central database.

## GitHub Pages
The web entry point is `index.html` in the repository root. GitHub Pages can publish it from the `main` branch/root after Pages is enabled in repository Settings → Pages.
