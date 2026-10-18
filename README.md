# StageProof website

Static site. GitHub Pages serves the `gh-pages` mirror at
https://sriramr90.github.io/stageproof-site/; the workflow in
`.github/workflows/pages.yml` mirrors `main` there on every push, so edit
`main` only. For a root-level URL, import this repository into Vercel or
Cloudflare Pages (framework "Other", no build command, output directory `.`).
The product itself lives in a separate private repository.
