# my-site — Draftly Export

## Files
- `index.html` — Main site file. Open directly in a browser or host on any static server.
- `bg-hero.*` — Hero background image used by the scroll animation engine.
- `frames-jpg/` — Individual frames for the scroll-driven background animation.
- `video.mp4` — Background video (if generated).
- `video-chain-*.mp4` — Additional video segments (if generated).
- `uploads/` — Your uploaded images referenced by the site.
- `generated-image-*.jpg` — AI-generated images used in the site.

## Self-Hosting

### Quickstart (no server needed)
```
open index.html
```
Works in most browsers for preview. Some features (fetch, video) require a local server.

### With a local static server
```bash
npx serve . -l 3000
# Then open http://localhost:3000
```

### With Python
```bash
python3 -m http.server 3000
# Then open http://localhost:3000
```

## Hosting
Deploy the entire folder to any static hosting provider:
- **Netlify**: Drag-and-drop the folder at netlify.com/drop
- **Vercel**: `npx vercel` in this folder
- **Cloudflare Pages**: Upload via the dashboard

---
Exported from Draftly · https://draftly.space
