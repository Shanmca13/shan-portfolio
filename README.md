# Shanmugasundaram C — Scrum Master Portfolio

A lightweight, responsive personal portfolio for recruiter-facing use. Built with plain HTML, CSS, and JavaScript—no framework, build step, or paid dependency required.

## Before publishing (important)

1. In `index.html`, replace `YOUR_EMAIL@example.com` with an email address you want recruiters to use.
2. Verify the LinkedIn URL `https://www.linkedin.com/in/shan-c/` and change it if your exact profile URL differs.
3. Verify each metric and add its measurement period/context before making the site public. Current draft uses these previously supplied figures: predictability 72% → 90%, Jira compliance 60% → 95%, and reporting effort −40%. Remove any metric you cannot substantiate.
4. Review credential names, status, and expiry dates before publishing. The site intentionally avoids listing expiry-sensitive credentials as currently valid without verification.
5. Add a résumé PDF only after checking it for confidential client, employer, project, or personal information. The first version does not include a résumé download because no approved PDF was supplied.
6. The website contains no employer/client names, internal ticket IDs, private project details, analytics trackers, or third-party fonts.

## Local preview

Open `index.html` in a browser. For a local server, from this directory run:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Publish with GitHub + Vercel

### 1. Create the GitHub repository

- Sign in to GitHub and create a new repository named `scrum-master-portfolio`.
- Choose Public if you want the source code visible, or Private if you prefer. A Vercel deployment can still be connected to a private repository.
- Upload `index.html`, `styles.css`, `script.js`, and `README.md` to the repository root, or use Git from your computer.

### 2. Deploy to Vercel

- Sign in to Vercel using your GitHub account.
- Choose **Add New → Project** and import `scrum-master-portfolio`.
- For this plain static site, no framework preset or build command is required. Leave the build command empty; use the repository root as the project root.
- Deploy. Vercel will provide a generated `*.vercel.app` URL. The exact name depends on availability and your project settings.
- After every push to the connected branch, Vercel can redeploy automatically.

### 3. Check the live site

- Test the navigation on mobile and desktop.
- Test LinkedIn and email links.
- Check that no placeholders remain.
- Confirm all metrics, claims, credential names, and links are accurate.
- Share the live URL in LinkedIn Contact info and Featured. If your LinkedIn account offers a custom website button, configure it separately.

## Suggested Git commands

```bash
git init
git add index.html styles.css script.js README.md
git commit -m "Create Scrum Master portfolio"
git branch -M main
git remote add origin https://github.com/YOUR_GITHUB_USERNAME/scrum-master-portfolio.git
git push -u origin main
```

Replace `YOUR_GITHUB_USERNAME` with your GitHub username before running the commands.

## Next iteration

Create one or two sanitized case studies using synthetic or aggregated data: (1) improving sprint predictability and work-item hygiene, and (2) simplifying delivery reporting. Each should explain the situation, your actions, how success was measured, and lessons learned—without disclosing protected information.
