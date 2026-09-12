# Flygram 🪰🦟

Flygram is an Instagram-inspired social network for insects.

## Included

- Instagram-style gradient UI: purple, pink, orange and yellow
- Responsive desktop + mobile layout
- Infinite-feeling social feed with insect posts
- Stories with full-screen viewer
- Profiles with posts, followers and follow state
- Explore grid and search
- Reels section
- Create-post modal
- Like / save / follow interactions persisted in `localStorage`
- Insects include bees, ladybugs, ants, butterflies, spiders, grasshoppers, mantises and mosquitoes
- GitHub Pages deployment workflow

## Local development

```bash
npm install
npm run dev
```

Production build:

```bash
npm run build
npm run preview
```

The app is intentionally frontend-only for this first complete version. Authentication, a real database, image uploads and server-side comments can be added later without changing the visual product direction.

## GitHub Pages

The deploy workflow lives in `.github/workflows/deploy.yml` and publishes the `dist` folder on pushes to `main`.
