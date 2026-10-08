# DiffuView — Project Page

Project page for **DiffuView: Multi-View Diffusion Pretraining for 3D-Aware Robotic Manipulation** (CVPR 2026).

Static site (plain HTML + CSS, no build step). Based on the
[Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template) / Nerfies style.

## Local preview

```bash
cd project_page
python3 -m http.server 8000
# open http://localhost:8000
```

## Structure

```
project_page/
├── index.html              # all content lives here
├── static/
│   ├── css/index.css       # styles
│   ├── images/             # figures from the paper
│   └── pdfs/               # paper + supplementary
```

## TODO before going public

- [ ] Fill in the **arXiv** link (hero buttons, `#` placeholder)
- [ ] Fill in the **Code (GitHub)** link
- [ ] Add author homepage links (currently `#`)
- [ ] (Optional) replace favicon
- [ ] (Optional) add a demo video section once ready

## Deploy to GitHub Pages

1. Create a repo and push the **contents of `project_page/`** to the root of a branch.
2. Repo → Settings → Pages → Source = your branch, folder = `/ (root)`.
3. Site will be live at `https://<user>.github.io/<repo>/`.
