# Orbit Quiz

Orbit Quiz is a self-contained space trivia game. Answer ten randomized questions about the solar system and space exploration, get instant feedback, and see your score and personal best.

## Run locally

No build tools, dependencies, or web server are required. Clone the repository and open `index.html` in a modern web browser:

```text
git clone https://github.com/ramn3nz/space-quiz.git
```

The quiz also works when opened directly from the repository folder. Your personal best is saved in the browser's local storage.

## Deployment

The GitHub Actions workflow in `.github/workflows/deploy-pages.yml` publishes the static site to GitHub Pages when changes are pushed to `main`.

For the first deployment, set the repository's **Settings → Pages → Build and deployment → Source** to **GitHub Actions**. The workflow requests the `pages: write` and `id-token: write` permissions it needs to deploy.
