# Pomodoro App

Built with React + Vite + TailwindCSS.

## Setup

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
npm run preview
```

## Deploy

- **GitHub Pages**: Use `gh-pages` or deploy `dist/` folder via GitHub Actions.
- **Netlify/Vercel**: Connect repository and set build command `npm run build`, publish `dist`.


## Added features

- Browser notifications and sound on session complete (placeholder sound file included).
- GitHub Actions workflow to build and deploy `dist/` to GitHub Pages on push to `main`.
- Standalone single-file `index-standalone.html` for quick hosting without a build step.
