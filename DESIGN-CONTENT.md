# YUHAN Portfolio — Deployment Notes

## Website

- Identity: 赵禹涵 / Lyon — Creative Designer
- Root entry: `index.html`
- Portfolio alias: `portfolio.html`
- Sections: Home, Selected Works, Visual Exploration, Contact
- Detail experiences: six selected-work pages, gallery image stacks, HMI video, Lottie motion collection, and emoji gallery
- Interactions: floating experience cards, accordion projects, masonry gallery, and full-screen detail overlays

## Assets

- Production assets are copied from `assets/` into the deployment package.
- Project and gallery artwork is local.
- Heavy images use optimized WebP versions where supported by the current design.
- Videos, GIFs, and Lottie JSON remain local and retain their original playback behavior.

## External dependencies

- Display fonts load from `fonts.bytedance.net`.
- Phosphor Icons loads from `unpkg.com`.
- If either CDN is unavailable, the website content and local artwork still load; typography/icons may use fallbacks.

## Upload

Upload the complete contents of this folder to the root directory of a static host. Do not upload only the HTML files: the `assets/` folder is required.
