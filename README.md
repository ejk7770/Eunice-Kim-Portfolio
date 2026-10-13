# Eunice Kim Portfolio

A responsive portfolio built with plain HTML, CSS, and browser JavaScript. It has no backend, framework runtime, package installation, or build step.

## View locally

Open `index.html` in a browser, or serve this folder with any static file server.

## Publish on GitHub Pages

The site is set up for <https://ejk7770.github.io/eunicekimportfolio/>.

1. Add these site files and the `.github/workflows/deploy.yml` workflow to the `main` branch of [ejk7770/eunicekimportfolio](https://github.com/ejk7770/eunicekimportfolio).
2. In the repository, open **Settings → Pages** and set the source to **GitHub Actions**.
3. Push to `main`, then check **Actions** for the deployment result.

The workflow copies the HTML pages, stylesheet, JavaScript, and images into a deployment folder, then publishes those files. There is no framework build or dependency installation.
