# AP Disaster Simulator

## Local development

```bash
npm install
npm run dev
```

## GitHub Pages deployment

This project is a Vite app, so GitHub Pages must serve the production build, not the source `index.html`.

1. Run `npm run build`.
2. Push the generated `docs` folder to GitHub.
3. In the GitHub repository settings, set Pages to deploy from the `main` branch and the `/docs` folder.

You can also publish with:

```bash
npm run deploy
```

That command builds the app and deploys the `docs` folder.
