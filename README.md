# Lee Ga-young — Portfolio

Infrastructure / Cloud Security Engineer portfolio site, built as a static HTML/CSS/JS site for GitHub Pages.

## Structure

- `index.html` — home page (hero, about, skills, project list)
- `project-1-aws-devsecops.html` — AI 기반 AWS DevSecOps 플랫폼
- `project-2-security-automation.html` — Rocky Linux & DB 시스템 보안 자동화
- `project-3-incident-response.html` — 보안 사고 원인 분석 및 대응 방안 도출

## Deploy to GitHub Pages

1. Create a new GitHub repository named `<your-username>.github.io` (must match your username exactly for a user site), or any name for a project site.
2. Push this folder's contents to the repo's `main` branch:
   ```
   git init
   git add .
   git commit -m "Initial portfolio site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```
3. In the repo Settings → Pages, set Source to "Deploy from branch", branch `main`, folder `/ (root)`.
4. Site will be live at `https://<your-username>.github.io/` (user site) or `https://<your-username>.github.io/<repo-name>/` (project site) within a few minutes.

No build step required — pure static HTML/CSS/JS.
