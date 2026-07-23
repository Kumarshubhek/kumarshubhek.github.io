# Kumar Shubhek Website — Sprint 0

The foundation for `www.kumarshubhek.com`, built with Astro and designed for static hosting such as GitHub Pages.

## Requirements

- Node.js 20 LTS or newer
- npm (installed with Node.js)

## Run locally

1. Extract this folder wherever you keep local projects.
2. Open a terminal in the extracted `kumarshubhek-website` folder.
3. Run:

   ```bash
   npm install
   npm run dev
   ```

4. Open the local URL shown in the terminal (normally `http://localhost:4321`).

## Useful commands

```bash
npm run dev       # Start the local development server
npm run check     # Check Astro and TypeScript files
npm run build     # Create the production site in dist/
npm run preview   # Preview the production build locally
```

## Structure

```text
public/             Static files: images, videos, résumé, favicon
src/components/     Reusable interface components
src/layouts/        Shared page layouts
src/pages/          Website routes; index.astro is the homepage
src/sections/       Page-level content sections
src/styles/         Global tokens and styling
src/scripts/        Browser-side JavaScript when required
src/data/           Content data used by the site
```

## Asset locations

- `public/images/hero/` — portrait and hero artwork
- `public/images/journey/` — career timeline visuals
- `public/images/ai/` — AI concepts and dashboard images
- `public/images/work/` — portfolio images, including YUVA LSP and UI examples
- `public/images/people/` — team, workshop, and event photos
- `public/images/insights/` — article images
- `public/videos/` — showreels and product demos
- `public/resume/` — downloadable résumé PDF

This sprint deliberately uses no UI framework or animation package. Later sprints can add only the libraries that are actually needed.
