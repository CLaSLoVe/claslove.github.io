
## Dian Jin – Academic Homepage

This repository is based on a fork of [RayeRen/acad-homepage.github.io](https://github.com/RayeRen/acad-homepage.github.io) and hosts the source code of my personal academic homepage, built with Jekyll and deployed via GitHub Pages at `https://claslove.github.io`.

The site focuses on:
- **Research** in Human–Computer Interaction and AI for Science.
- **Publications** organized by category with per-paper importance levels.
- **News, experience, and awards** in a clean, modern single-page layout (`_layouts/landing.html`).

## Local Development

Prerequisites:
- Ruby, RubyGems, a C compiler (GCC/Clang), and Make.

To run the site locally:
1. Install dependencies:
   ```bash
   bundle install
   ```
2. Start the development server:
   ```bash
   bash run_server.sh
   ```
3. Open `http://127.0.0.1:4000` in your browser. The site will reload automatically when you edit files.

Key content/configuration files:
- `_config.yml` – site-wide settings (title, author info, analytics, etc.).
- `_data/home.yml` – data for the landing page (about, news, education, publications, awards, life).
- `_layouts/landing.html` – custom landing page layout and styles.
- `_pages/about.md` – about page in the default Minimal Mistakes layout.

## Credits

This homepage is customized from the **AcadHomepage** template by Raye Ren (`RayeRen/acad-homepage.github.io`) and builds on the Minimal Mistakes Jekyll theme and related open‑source projects (see `LICENSE`). 
