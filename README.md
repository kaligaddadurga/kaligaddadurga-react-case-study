# React Case Study - PDF Highlight

This repository contains a small React application that shows a PDF on the left and an analysis panel on the right.
Clicking the reference [3] in the analysis panel overlays a yellow highlight on the target area in the PDF.

## Files
- `public/maersk.pdf` - The PDF provided by the user (included).
- `src/` - React source files.

## How to run locally
1. Unzip the project and open the folder.
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run in development:
   ```bash
   npm start
   ```

## How to deploy (Vercel)
1. Upload this repository to GitHub (create a new repo and drag & drop the files).
2. On Vercel (https://vercel.com) click "Add New Project" → Import from GitHub → select the repo → Deploy.
3. Vercel will provide a deployment URL (example: `https://react-case-study-yourname.vercel.app`).

## How to deploy (Netlify)
1. Create a new site from Git via Netlify dashboard and connect your GitHub repo.
2. Build command: `npm run build`, Publish directory: `build`
3. Deploy.

## Notes
- The highlight coordinates in `src/AnalysisPanel.js` are approximate. You may need to tweak the `top/left/width/height` values to fit the exact PDF rendering depending on screen size and scale.

