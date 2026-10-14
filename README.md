# Horror Story AI

A mobile-responsive, glassmorphism horror-story creator built with plain HTML, CSS and JavaScript. Designed to deploy directly to GitHub Pages without a build step.

## Features
- Hindi, English and Hinglish story templates
- Six horror categories and three story lengths
- Tone selector, scene-by-scene cinematic prompt library
- Save favorites in browser localStorage
- Copy, share-ready text, and TXT download
- Dark/light theme toggle
- Responsive mobile navigation and layouts
- No dependencies, build tools, or API key required

## Run locally
Open `index.html` in a modern browser.

## Deploy to GitHub Pages
1. Create a public repository named `horror-story-ai` (or use an existing repository).
2. Upload `index.html` and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/(root)`, then click **Save**.
6. Wait for the Pages deployment to finish. Your URL will look like `https://YOUR-USERNAME.github.io/horror-story-ai/`.

## Important
This version generates stories from built-in local templates; it does not call a real AI model. Favorites are stored only in the current browser/device. GitHub Pages is static hosting and does not run server-side code. For real AI generation, add a separate backend/serverless function and keep provider API keys on the server—never in public client-side JavaScript.

## Suggested next upgrades
- Add more varied story templates and user-editable prompts
- Add export to Markdown and print-friendly layout
- Connect a secure serverless API for actual AI-generated stories
- Add a content disclaimer and report/feedback link
