# GitHub setup – first upload

## 1. Create the repository

1. Sign in to GitHub.
2. Create a new repository named `system-design-sde1`.
3. Choose **Public** only if you are comfortable making the notes and simulations visible to everyone. Otherwise choose **Private**; do not enable public GitHub Pages for material you want to keep private.
4. Create it without adding a README, license, or `.gitignore` because this folder already contains those files.

## 2. Push this folder using Git

Extract the ZIP. Open Git Bash or a terminal inside the extracted `system-design-sde1` folder and run:

```bash
git init
git add .
git commit -m "Add Topic 01 Client-Server Architecture"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/system-design-sde1.git
git push -u origin main
```

Replace `YOUR_USERNAME` with your GitHub username. GitHub may ask you to sign in through your browser or credential manager. Never paste a password or personal access token into this repository or into chat.

## 3. Optional: publish simulations as clickable web links

The interactive simulation can be opened locally from `docs/topics/01-client-server/index.html`. To publish it as a website:

1. Open the repository on GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch `main` and folder `/docs`, then save.
5. After GitHub Pages finishes publishing, open the site URL shown on the Pages settings screen. The simulation will be at:

   `https://YOUR_USERNAME.github.io/system-design-sde1/topics/01-client-server/`

GitHub Pages sites are public on the internet. With GitHub Free, Pages is available for public repositories. Check the current GitHub Pages documentation if the settings differ: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## 4. Add future topics

For each completed topic:

1. Add the Word notes under `topics/02-topic-name/`.
2. Add the interactive simulation at `docs/topics/02-topic-name/index.html`.
3. Update the completed-topics table in the root `README.md`.
4. Commit and push:

```bash
git add .
git commit -m "Add Topic 02 - HTTP REST and DNS"
git push
```

Use the real topic number and name in the commit message. Do not commit unfinished notes as completed.
