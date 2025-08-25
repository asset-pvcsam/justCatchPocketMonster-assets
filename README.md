# justCatchPocketMonster assets

This repository is dedicated **only to storing assets** (such as imagesused by the main project: [justCatchPocketMonster](https://github.com/pvcsam/justCatchPocketMonster).

## 📂 Structure

```
/assets
  ├── images/
  └── ...
```

* `images/` → Project images

## 🔗 How to Access Assets

You can access files directly via **GitHub’s raw content delivery**:

```
https://raw.githubusercontent.com/<username>/<repo>/<branch>/<path-to-file>
```

### Example

If you want to use `assets/images/logo.png` from the `main` branch:

```
https://raw.githubusercontent.com/<username>/<repo>/main/assets/images/logo.png
```

This URL can be embedded directly into websites, applications, or documentation.

## 🚀 Usage

These assets are intended to be **read-only** and should not contain any code.
If you want to contribute or update files:

1. Fork the repo
2. Add or update assets in the appropriate folder
3. Open a pull request

## ⚠️ Notes

* Keep file names descriptive and lowercase (e.g., `logo-dark.png`, `map-data.json`).
* For Pokémon's images, use the format `<four-digit ID>-<three-digit version>.png` (Example: `0001-001.png`).
* (Optional) For shiny versions, append `-shiny` at the end. (Example: `0001-001-shiny.png`)
* (Optional) For form versions, append `-<form>` at the end (before shiny). (Example: `0001-001-mega-shiny.png`)
* Avoid committing large files (>50MB) as GitHub does not support them.
