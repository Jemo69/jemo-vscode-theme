# Jemo VS Code Theme

A dark Visual Studio Code theme generated from the palette in `colors.md`.

## Build

```bash
npm ci
npm run package
```

## Install from VSIX

```bash
code --install-extension jemo-theme-0.0.2.vsix
```

Then select **Jemo** from **Preferences: Color Theme**.

## Release and Marketplace Publish

The workflow in `.github/workflows/release-vsix.yml` builds a VSIX, uploads it as an artifact, and attaches it to a GitHub Release when you push a tag like `v0.0.2`.

To publish to the Visual Studio Marketplace, add a repository secret named `VSCE_PAT` with a Marketplace Personal Access Token. Tagged releases publish automatically; manual runs can publish by enabling the `publish_marketplace` option.
