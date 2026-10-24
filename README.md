# Software Engineering Portfolio

A creative, responsive portfolio built with React, Vite, Tailwind CSS, and lucide-react.

## Run locally

1. Install Node.js 18+ (Node.js 20 LTS or newer recommended).
2. Open a terminal in this folder.
3. Run `npm install`.
4. Run `npm run dev`.
5. Open the local URL printed by Vite (usually http://localhost:5173).

## Customize before publishing

- Edit the `profile` object near the top of `src/main.jsx` to add your actual GitHub, LinkedIn, and email links.
- Edit `projects` to add verified GitHub and live demo links, and update descriptions as the apps evolve.
- Check all experience descriptions and dates for accuracy.
- To add a resume, put `resume.pdf` in `public/` and add a resume button linking to `/resume.pdf`.
- No placeholder contact links are clickable until real URLs are supplied.

## Production build

Run `npm run build` and `npm run preview` to check the output. Deploy to Vercel by importing this repository, choosing the Vite framework preset, build command `npm run build`, and output directory `dist`.

The Google Fonts import requires an internet connection; fallback system fonts are provided.

## Links
GitHub, LinkedIn, email, PharmaLingo landing page, and resume are configured.
AutoMatch AI repository and demo links are intentionally left blank until you provide the exact URLs.
To update them, edit the `projects` array in `src/main.jsx`.
