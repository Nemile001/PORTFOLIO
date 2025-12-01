```markdown
# Sonia Danjuma Nemile — Portfolio

This repository contains a single-page portfolio site (Tailwind + Chart.js via CDN).

Published location (after push & Pages enabled):
- https://sonia-danjuma.github.io

Included files:
- index.html — main site
- assets/profile.jpg — profile image (save the uploaded image here)
- README.md — this file

Notes:
- No custom domain configured.
- GitHub Pages for a user site will serve the site from the repository root on the main branch.

How to publish locally (exact commands)
1. Create the repository on GitHub with name: `sonia-danjuma.github.io` under the account `Nemile001`.
   - Web: go to https://github.com/new and create a public repository named `sonia-danjuma.github.io` owned by Nemile001.
   - Or with GitHub CLI:
     - gh repo create Nemile001/sonia-danjuma.github.io --public --confirm

2. In your local project folder (with index.html, README.md and assets/profile.jpg) run:
   - git init
   - git add .
   - git commit -m "Initial portfolio site"
   - git branch -M main
   - git remote add origin https://github.com/Nemile001/sonia-danjuma.github.io.git
   - git push -u origin main

3. Wait a minute, then visit: https://sonia-danjuma.github.io

Troubleshooting / notes
- If the repo already exists and you get a permission error, ensure you are signed in to the Nemile001 account or have collaborator access.
- GitHub Pages for a user-site repo (owner.github.io) serves the root automatically; no extra Pages configuration is required in most cases. If Pages is not enabled automatically, go to Settings → Pages and set Source = main branch / root.
- If images appear missing, verify assets/profile.jpg exists and is committed.
- Optionally optimize assets/profile.jpg (resize to ~400px wide, compress to reduce page load).

If you want me to retry the automated creation/push after you create the empty repo in your Nemile001 account, reply "retry" and I will attempt the automated publish again immediately.
```