# Browser Image Preflight

Browser Image Preflight is a small companion utility for the browser-based watermark-removal workflow at [MarkVanish](https://markvanish.com/). It helps a visitor inspect an image before editing: file type, file size, pixel dimensions, and a local preview are shown before any export.

No image is uploaded by this utility. It runs entirely in the browser and can export the selected image as PNG.

## Run it

Download `image-preflight.html` and open it in any modern browser. There is no build step and no server to configure.

## Useful checks before editing an image

- Confirm that the file is the intended one and inspect its dimensions.
- Keep a copy of the original before exporting a new PNG.
- Make sure you have the right to edit the image and remove any marks or overlays.

## Files

- `image-preflight.html` — local, reusable inspection and PNG-export tool.
- `browser-image-workflow-checklist.csv` — a compact review checklist for browser-based image tools.
- `watermark-removal-review-checklist.md` — a plain-language checklist for checking an editing workflow before publishing it.

## License

MIT. See [LICENSE](LICENSE).
