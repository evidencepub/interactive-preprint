# Intreactive Preprint Template

This repository provides a Evidence-compatible article template using MyST (Markedly Structured Text) for creating interactive scientific preprints.

https://evidencepub.github.io/interactive-preprint

## Learn the ropes of MyST through GitHub Actions

This repository includes a GitHub Actions workflow that builds the MyST-formatted preprint and publishes it to GitHub Pages. 

> [!TIP]
> To enable this, you need to enable GitHub Pages in the repository settings (select GitHub Actions as the `Build and deployment` source).

Once you push your changes to the `main` branch, the GitHub Actions workflow will build the MyST-formatted preprint and publish it to your GitHub Pages.

> [!WARNING]
> The actions file (`.github/workflows/deploy.yml`) attempts to **execute** the executable content in this preprint. However, this doesn't always work smoothly in the GitHub Actions environment, as it requires starting a Jupyter Server and connecting to it. In other words, it may not generate the interactive figures as intended. Nevertheless, any changes you make to the **narrative** content will be reflected in the preprint.

The ultimate guide for authoring narrative and executable content in MyST documents is the [MyST Guide](https://mystmd.org/guide). 