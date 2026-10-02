# Romantic Proposal Website

Open `index.html` with Live Server.

## Folder structure

- `index.html` — cleaned website
- `images/our-photo.jpg` — the photo extracted from the original HTML

The original HTML contained 5 embedded Base64 JPEG copies, but all 5 copies were identical. They now use the same external image file, which keeps the HTML much smaller.

If you want different photos for the five image locations later, duplicate `our-photo.jpg`, give each copy a different name, and change the corresponding `<img src="...">` in `index.html`.
