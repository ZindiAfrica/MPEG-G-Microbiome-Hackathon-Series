# MPEG-G Microbiome Hackathon Series — showcase site

Static GitHub Pages site presenting the winning solutions from the two
MPEG-G Microbiome Hackathon Series competitions hosted on Zindi in 2025.

## Contents

```
index.html                    the showcase page
assets/css/site.css           styles (IBM Plex Sans, 11pt body)
assets/img/                   logos, challenge banners, source-study figures
solutions/challenge-2/        winning solution code for Challenge 2 tracks
.nojekyll                     serve files as-is, no Jekyll processing
CONTENT-GAPS.md               open questions and unverified facts
```

Challenge 1 solutions live in the winners' own repositories and are linked
from the page rather than vendored here.

## Publishing

```bash
git init
git add .
git commit -m "Initial showcase page"
git branch -M main
git remote add origin git@github.com:<org>/<repo>.git
git push -u origin main
```

Then in the repository settings, under Pages, set the source to
`Deploy from a branch`, branch `main`, folder `/ (root)`.

The site will appear at `https://<org>.github.io/<repo>/`.

## Local preview

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Before publishing

Read `CONTENT-GAPS.md`. Several figures in the source material contradict
each other and a few facts are unverified.
