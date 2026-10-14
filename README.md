# linshanify.github.io

Personal homepage of Lin Shan, served at [linshanify.github.io](https://linshanify.github.io).

## How it works

- **Source of truth**: `Profile/Homepage/Homepage.md` in the SecondBrain vault
- **HTML**: `index.html` (generated and maintained by AI)
- **Deployment**: Push to `main` → GitHub Actions auto-deploys to `gh-pages` branch

## Updating

To update the homepage, say **`/homepage-export`** in Claude Code.  
The AI will read the vault content, update `index.html`, and push to GitHub.

## Files

```
.
├── index.html          ← The homepage (AI-maintained)
├── assets/
│   └── img/
│       └── profile.png ← Profile photo
└── .github/
    └── workflows/
        └── deploy.yml  ← Auto-deploy to gh-pages on push
```
