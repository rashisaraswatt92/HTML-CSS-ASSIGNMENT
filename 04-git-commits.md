# Assignment 04 — Git commits

Use meaningful messages that describe each change. Example workflow:

```bash
git init
git add .
git commit -m "Add initial HTML assignment files"
git add 06-basic-page.html 07-resume-text-only.html
git commit -m "Complete basic page and text resume"
git add 08-resume-semantic.html 09-debug-buggy-html.html
git commit -m "Add semantic resume and corrected HTML"
```

Then connect the local project to your own GitHub repository and push it:

```bash
git branch -M main
git remote add origin YOUR_REPOSITORY_URL
git push -u origin main
```

Replace `YOUR_REPOSITORY_URL` with your own repository URL. Do not use a remote URL unless it belongs to your account.
