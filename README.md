# Depot website

The product page for Depot, served by GitHub Pages from the `main` branch root. Plain HTML and CSS, no build step.

Screenshots in `assets/shots/` are taken from the app's browser mode (`pnpm dev`, mock data) in light and dark; the page swaps them with `prefers-color-scheme`. Colors and type are the Obsidian tokens the app uses (`src/styles/tokens.css` in the app repo).

The other-machines shots (`machines-*`, `remote-*`) use the same mock with two saved machines and canned agent answers passed to `createMockApi` (`machines`, `remote`); that setup lives only in the screenshot session, not in the app repo.
