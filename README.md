# NumaCore — site source

Static site source for **[numacore.ca](https://numacore.ca)** — the platform brand for long-range component planning on mobile mining fleets.

Single-file static HTML, vanilla CSS. No build tools, no JS framework. Drag-and-drop deployable to any static host.

## Pages

| File | Role |
|---|---|
| `index.html` | Home — wordmark hero, platform overview, Stride + Lens cards |
| `platform.html` | Architecture cascade: NumaCore → Stride → Lens |
| `lens.html` | The five-panel internal delivery engine |
| `stride.html` | PCR as a Service — the retainer offering |
| `origin.html` | Why NumaCore exists |
| `contact.html` | Platform-level enquiries |
| `styles.css` | Shared stylesheet (NumaCore brand pack v1 tokens) |

## Local review

Double-click `index.html` to open in any modern browser. The site has no server-side or build dependencies — it runs straight from the filesystem.

## Tech notes

- Mobile-responsive from v0.1 (breakpoints at 880px / 700px)
- CSS-only hamburger nav (no JS)
- Inline-SVG icons and favicon (no asset files required)
- Hex-grid backdrop, glow-blob atmosphere, film-grain noise overlay
- Honours `prefers-reduced-motion`

## Brand & relationship

NumaCore is the proprietary planning platform behind [Birchwood Advisory](https://birchwood-advisory.com)'s long-range planning service. It is not licensed as a standalone product.
