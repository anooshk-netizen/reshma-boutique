# Reshma Boutique — three website directions

Four pages, no build step, no dependencies.

- `index.html` — the chooser page. Explains all three options and links to them.
- `option-1.html` — The Atelier. Top navigation, split hero, animated.
- `option-2.html` — The Rail. Fixed left sidebar navigation.
- `option-3.html` — The Lookbook. Minimal top bar, overlay menu, centred logo.

## Put it on GitHub Pages

1. Make a new public repo, e.g. `reshma-boutique`.
2. Upload all four HTML files to the root of the repo (drag and drop works on github.com).
3. Repo → Settings → Pages → Source: "Deploy from a branch" → Branch: `main`, folder `/ (root)` → Save.
4. Wait about a minute. The site is at `https://<your-username>.github.io/reshma-boutique/`

Send the client that link. It opens on the chooser page.

## Before it goes live

- Replace the WhatsApp number. Search for `910000000000` (used in every link) and `+91 00000 00000` (shown as text) in all four files.
- Replace the placeholder garment drawings with real photos. In each tile, swap the `<svg class="gs">` for `<img src="your-photo.jpg" alt="...">`. The `.ph img` CSS rule is already in place.
