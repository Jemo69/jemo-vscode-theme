# Jemo VS Code Theme

A dark Visual Studio Code theme generated from the palette in `colors.md`.

## Build

```bash
npm ci
npm run package
```

## Install from VSIX

```bash
code --install-extension jemo-theme-0.0.1.vsix
```

Then select **Jemo** from **Preferences: Color Theme**.

## GitHub Actions

The workflow in `.github/workflows/vsix.yml` builds the VSIX on pushes and pull requests, uploads it as an artifact, and attaches it to a GitHub Release when you push a tag like `v0.0.1`.
