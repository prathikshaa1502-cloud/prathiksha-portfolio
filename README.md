# Prathiksha A — Portfolio

A responsive React + Vite personal portfolio, designed around the connection between content, technology, and research.

## Run locally

1. Install Node.js (LTS recommended).
2. In this folder, run `npm install`.
3. Run `npm run dev` and open the local URL Vite prints.
4. Run `npm run build` to create the production site in `dist/`.

## Deploy to Netlify

1. Push this project to a GitHub repository.
2. In Netlify, choose **Add new site → Import an existing project** and connect that repository.
3. Build command: `npm run build`; publish directory: `dist`. `netlify.toml` already includes these settings and an SPA redirect.
4. Netlify Forms is configured for the `portfolio-contact` form. After the first deployment, submit a test message and confirm it appears in the site's Forms area in Netlify. Netlify may need form detection enabled/available for the site; the hidden form in `index.html` is included for build-time detection.

## Before public launch

- Verify the LinkedIn URL and contact email in `src/main.jsx`.
- Add GitHub profile/repository links when ready.
- Add real workshop name/date if available.
- Add specific stock-analysis methods and outputs only when documented.
- Publish the essay only after the draft and sources are ready.
- The drug–drug interaction project is labelled as research in progress; it does not claim a validated prediction model. Do not use experimental predictions for medication decisions.

## Contact form note

The contact form validates required fields and email format in the browser and submits to Netlify Forms using a URL-encoded POST. It requires the deployed site to be hosted on Netlify with Forms support enabled. Test the form after deployment; during local development it will not reach Netlify's form handler.
