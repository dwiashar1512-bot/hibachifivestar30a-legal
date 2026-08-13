# hibachifivestar30a-legal

This folder contains the legal pages for Hibachi Five Star 30A (privacy policies and Terms of Service), ready to publish via GitHub Pages.

How to publish (option A: using `gh` CLI):

1. Install Git and GitHub CLI (`gh`) and authenticate: `gh auth login`.
2. From this folder run:

```
cd hibachifivestar30a-legal
gh repo create YOUR_GITHUB_USERNAME/hibachifivestar30a-legal --public --source=. --push
```

3. In the repository settings on GitHub, enable GitHub Pages serving from `main` branch (root) or `gh-pages` as created by the `gh` command.

How to publish (option B: manual remote):

```
cd hibachifivestar30a-legal
git init
git add .
git commit -m "Add legal pages"
# Create an empty repo on GitHub via web, then:
git remote add origin https://github.com/YOUR_GITHUB_USERNAME/hibachifivestar30a-legal.git
git branch -M main
git push -u origin main
```

After pushing, go to repository Settings → Pages and set source to `main` branch → `/ (root)` and save.

The following URLs will be available (after GitHub Pages is active):

- https://YOUR_GITHUB_USERNAME.github.io/hibachifivestar30a-legal/privacy-policy-hibachi-en.html
- https://YOUR_GITHUB_USERNAME.github.io/hibachifivestar30a-legal/privacy-policy-hibachi-meta-short.html
- https://YOUR_GITHUB_USERNAME.github.io/hibachifivestar30a-legal/terms-of-service-hibachi.html

Replace `YOUR_GITHUB_USERNAME` with your GitHub username.
