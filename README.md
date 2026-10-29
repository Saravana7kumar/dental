# Lumina Dental — 3D dental clinic website

Fully offline libraries: three.js, GSAP and the font are bundled in `libs/` and `fonts/`.

## Run
1. EXTRACT the zip first.
2. Double-click `index.html`, or run `npx serve .` in this folder.

## Automatic booking emails (no mail app opens)
1. Open `index.html`, find `const MAIL='hello@luminadental.in'` and put the DOCTOR'S real email.
2. Put the site online (drag this folder onto Netlify, or use Vercel/GitHub Pages). Form sending works best from a hosted https site.
3. Submit one test booking. FormSubmit emails the doctor a one-time activation link; click it once.
4. After that, every "Book appointment" click arrives in the doctor's inbox automatically.
If sending ever fails, the page shows a "send by email instead" link as a fallback.
