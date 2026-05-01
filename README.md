# Uditha & Samadhi Wedding Invitation

Static wedding invitation website built with HTML, CSS, and vanilla JavaScript.

## Overview

This project is a personalized wedding invitation for:

- Groom: Uditha
- Bride: Samadhi
- Venue: Amaya Grand, Giriulla

The site includes:

- Landing and welcome screen
- Couple introduction
- Love story section
- Event details and embedded map
- Photo gallery
- Contact section for the bride and groom

Admin, dashboard, API, and comment features have been removed, so this project is now a clean static site suitable for GitHub Pages.

## Project Structure

```text
assets/     Images, music, and gallery files
css/        Stylesheets
js/         Frontend JavaScript source
index.html  Main invitation page
```

## Local Development

Install dependencies:

```bash
npm install
```

Run the local dev server:

```bash
npm run dev
```

Open:

```text
http://localhost:8080
```

## Build

Generate the production bundle:

```bash
npm run build
```

## Customize

Main places to edit:

- `index.html`
  Update names, text, event details, contact numbers, and section content.
- `assets/images/bg_carrousal/`
  Replace or add desktop carousel and gallery photos.
- `assets/images/`
  Replace profile, background, icon, and other invitation images.
- `js/app/guest/guest.js`
  Update carousel image list or client-side behavior if needed.

## GitHub Pages Deployment

This site can be deployed directly as a static GitHub Pages project.

### Option 1: Deploy from the repository root

1. Push the project to GitHub.
2. Open the repository on GitHub.
3. Go to `Settings > Pages`.
4. Under `Build and deployment`, choose:
   - `Source: Deploy from a branch`
   - `Branch: main`
   - `Folder: / (root)`
5. Save the settings.

GitHub Pages will publish `index.html` from the root of the repository.

## Notes

- This project currently uses no backend.
- The invitation works as a fully static website.
- If you change JavaScript source files in `js/`, run `npm run build` again so `dist/guest.js` is updated.

## License

This project is provided for personal use and customization.
