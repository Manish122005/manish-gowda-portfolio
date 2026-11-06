# Manish Gowda — Personal Portfolio

A responsive dark portfolio built with React, Vite and Tailwind CSS (Vite plugin), with custom CSS styling and Lucide icons.

## Included
- Responsive navigation and page sections
- Profile photo and downloadable resume
- About, skills, upcoming internship, projects, education, certifications and contact
- DocMind highlighted as the featured project
- GitHub, LinkedIn, email and AI Career Copilot demo links

## Run locally

Requirements: Node.js 20.19+ or 22.12+ recommended.

```bash
npm install
npm run dev
```

Open the local URL printed by Vite (usually http://localhost:5173).

To create a production build:

```bash
npm run build
npm run preview
```

The production site is generated in `dist/`.

## Deploy to Vercel
1. Create a GitHub repository, for example `manish-gowda-portfolio`.
2. Upload/push the contents of this folder to the repository.
3. Sign in to Vercel and choose **Add New → Project**.
4. Import the repository. Vercel should detect Vite automatically.
5. Use build command `npm run build` and output directory `dist`.
6. Deploy. Vercel will provide a public URL.

## Deploy to GitHub Pages
GitHub Pages can host this static portfolio. For a repository named `manish-gowda-portfolio`, set the Vite base path to `/manish-gowda-portfolio/` in `vite.config.js` before building, then configure GitHub Pages to deploy the `dist` folder using a GitHub Actions workflow. Vercel is the simpler first deployment option.

## Before publishing — verify these details
- Confirm the currently deployed AI Career Copilot demo still responds: https://ai-career-copilotsz.onrender.com/login
- DocMind is linked to its GitHub repository, but no public demo URL has been supplied yet.
- DSA Mentor AI repository URL has not been supplied.
- Sentinel repository URL has not been supplied.
- Smart ICU and Photon descriptions are intentionally limited because full implementation details/repository URLs have not yet been confirmed.
- The Conneqtions internship is labelled upcoming (expected January 2027), not completed experience.
- Review the bundled resume PDF and replace it if a newer approved version should be public.

## Update content
Edit project data, skills and certification arrays in `src/main.jsx`. Replace files in `public/assets/` to update the photo or resume. Keep the filenames the same, or update the references in `src/main.jsx`.
