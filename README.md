# Rachana S B — Developer Portfolio

A minimal, responsive personal portfolio built with **React, Vite, Tailwind CSS, and Lucide icons**.

## Requirements
- Node.js 20.19+ or 22.12+ (Node.js 24 is also supported)
- VS Code (recommended)

## Run locally in VS Code
1. Extract the ZIP file.
2. Open the `rachana-portfolio` folder in VS Code (`File > Open Folder`).
3. Open a terminal (`Terminal > New Terminal`).
4. Run:

```bash
npm install
npm run dev
```

5. Open the localhost URL shown in the terminal (usually `http://localhost:5173`).

## Customize your information
- **Name, email, GitHub, LinkedIn, location:** edit `PROFILE` near the top of `src/App.jsx`.
- **Projects:** edit the `projects` array in `src/App.jsx`. Set each `link` to its actual GitHub repository or live-demo URL. Do not publish placeholder URLs.
- **Skills:** edit `skills` in `src/App.jsx`.
- **Experience:** edit `experience` in `src/App.jsx`.
- **Resume:** replace `public/resume.pdf` with your latest resume, keeping the filename the same.
- **Colors and typography:** edit `tailwind.config.js` and `src/index.css`.
- **Profile photo:** the hero intentionally uses an initials-based graphic. Add a photo only if desired.

The first three project summaries are based on previously discussed project details; review them before publishing. The remaining four projects, training, education, and certifications are taken from the supplied resume. The LinkedIn URL and individual project links are intentionally blank until confirmed.

## Production build

```bash
npm run build
npm run preview
```

The production site is generated in `dist/`.

## Deploy with Vercel
1. Push this folder to a new GitHub repository.
2. Sign in to https://vercel.com and choose **Add New > Project**.
3. Import the repository.
4. Framework preset: **Vite**. Build command: `npm run build`. Output directory: `dist`.
5. Click **Deploy**.

## Deploy with Netlify
1. Push this folder to GitHub.
2. In https://app.netlify.com choose **Add new project > Import an existing project**.
3. Select the GitHub repository.
4. Build command: `npm run build`; publish directory: `dist`.
5. Click **Deploy**.

## GitHub push example

```bash
git init
git add .
git commit -m "Initial portfolio"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git push -u origin main
```

Create an empty GitHub repository first and replace `YOUR_USERNAME` and `YOUR_REPO` with your actual values.
