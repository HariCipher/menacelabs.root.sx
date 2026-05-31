# harilal.root.sx

soc analyst · detection engineer · purple team

→ [hari.root.sx](https://hari.root.sx) *(or your chosen domain)*

---

## structure

```
harilal.root.sx/
├── .github/
│   └── workflows/
│       └── static.yml     ← auto-deploys to GitHub Pages on push
├── assets/
│   └── favicon.svg
├── favicon.svg
├── index.html             ← entire site
├── project-data.json      ← edit this to update projects
└── README.md
```

## update projects

edit `project-data.json` — push — done. no rebuild needed.

## deploy

repo → Settings → Pages → Source: **GitHub Actions**  
push to `main` → workflow fires → live in ~30s.

## custom domain (GitHub Pages)

repo → Settings → Pages → Custom domain → `yourdomain.com`  
then add a CNAME record at your DNS provider pointing to `HariCipher.github.io`
