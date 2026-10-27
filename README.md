# TV Focus Lab

A 2560 × 1440 visual sandbox for TV show cards and circular app-icon focus effects.

## Preview

Open `index.html` directly in a browser, or enable GitHub Pages at **Settings → Pages → Build and deployment → Deploy from a branch → main → /(root) → Save**. Once published, the page URL should be `https://mrriskyclick.github.io/UiTest/`.

## Edit content

Click a tile, then **Add / Edit image**. Change its title, load an image URL, upload an image, paste an image, or drag an image into the editor. Drag to adjust crop and use the slider to zoom, then select **Apply**.

Edits are stored in your current browser's localStorage where capacity permits. **Export configuration** creates a JSON backup including embedded image data; **Import configuration** restores a matching JSON backup. Large images can exhaust localStorage, so export the configuration after making changes. Consider using externally hosted image URLs for a smaller backup.

## Moving from the original ChatGPT preview

The original inline preview's image data and crop parameters are internal to that running browser widget and cannot be read remotely by the GitHub connector. They cannot be automatically transferred into this site. The images must be imported or re-added, or an export feature must be added to the old widget first.

## Development

The app is entirely self-contained in `index.html`, with no build step. GitHub commits maintain an edit history.
