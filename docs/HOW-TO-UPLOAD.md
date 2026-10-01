# How to upload (≈10 minutes)

> **Already pushed?** This repo is set up for the profile layout. Just rename it:
> repo **Settings → General → Repository name** → `Dhrumil-Kharadi` → **Rename**,
> then do step 3 (snake) and step 4 below.

## 1. Create your profile repo
1. Go to **github.com/new**
2. Repository name: **`Dhrumil-Kharadi`** (exactly your username — GitHub shows a
   "✨ special repository" message when it's right)
3. **Public**, don't add a README → **Create repository**

## 2. Upload the files
On the new repo page click **uploading an existing file**, then drag in
**everything inside the `Dhrumil-Kharadi` folder** (not the folder itself):

```
README.md
assets/            (header, stack, achievements, projects/, résumé)
.github/workflows/snake.yml
```

> The `.github` folder is hidden on Windows drag-and-drop sometimes. If it doesn't
> upload: in the repo click **Add file → Create new file**, type the name
> `.github/workflows/snake.yml`, and paste the contents of that file.

Commit to **main**.

## 3. Turn on the contribution snake
1. Repo → **Settings → Actions → General → Workflow permissions** →
   select **Read and write permissions** → Save
2. Repo → **Actions** tab → **Generate contribution snake** → **Run workflow**
3. Wait ~1 minute. It creates an `output` branch and the snake appears on your
   profile (it then refreshes itself every 12 hours).

## 4. Finish the rest
Open `PINNED-REPOS.md` and work through it — pins, repo descriptions, topics,
profile settings and photo.

## Optional: use git instead of drag-and-drop
```bash
cd D:\portfolio\github-profile\Dhrumil-Kharadi
git init -b main
git add .
git commit -m "Profile README"
git remote add origin https://github.com/Dhrumil-Kharadi/Dhrumil-Kharadi.git
git push -u origin main
```
