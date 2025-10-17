# TaskFlow

A small front-end project scaffold for TaskFlow. This repository contains a minimal HTML/CSS app using Tailwind CSS for styling.

## Project structure

- `index.html` - The main HTML page.
- `src/` - Source files for CSS and other assets.
  - `input.css` - Tailwind input CSS file.
- `img/` - Images used by the site.
- `package.json` - Project scripts and dev dependencies.

## Prerequisites

- Node.js (recommended v16+)
- npm (bundled with Node.js)

## Install dependencies

Run in repository root (PowerShell):

```powershell
npm install
```

## Development (build CSS)

This project uses Tailwind CSS. There is a script to build/watch the CSS:

```powershell
npm run build:css
```

This runs Tailwind CLI and watches `./src/input.css`, outputting compiled CSS to `./dist/output.css`.

If `dist/` is not referenced in `index.html`, you can either update `index.html` to include `dist/output.css` or copy the output into your preferred path.

## Test

There are no automated tests configured. The default `npm test` prints an error placeholder.

## Contributing

- Open an issue for bugs or feature requests.
- Send a pull request with a clear summary of changes.

## Notes

- Tailwind CLI dependency versions are defined in `package.json`.
- If you plan to deploy, consider adding a simple local server (`npx http-server` or similar) or integrate into a build tool.
