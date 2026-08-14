# Data Analyst Portfolio

A single-file, dependency-free HTML portfolio built for GitHub Pages. No build step — edit `index.html` and push.

## 1. Personalize the content

Search `index.html` for these spots and replace with your own info:

- **Name & title** — `<title>` tag, nav logo, hero eyebrow/headline
- **Hero stats** — the 4 numbers in the `.dash-card` widget (years experience, dashboards shipped, impact $, hours automated)
- **Toolkit bullets** — adjust the skill bullets under Excel / SQL / Power BI / Python to match your actual experience
- **Projects** — there are 8 sample project cards (2 per tool). Replace title, problem statement, impact bullets, tech chips, and the two link `href="#"` values with real links to your GitHub repos, Power BI public reports, or write-ups
- **Certifications** — swap in your real certs/degree
- **Contact section** — email, LinkedIn, GitHub links
- **Résumé button** — currently links to `resume.pdf`; add your résumé PDF to this folder with that filename, or change the `href`

Tip: `Ctrl/Cmd+F` for `EDIT ME`, `[Your`, and `#` link placeholders to find everything quickly.

## 2. Add real project evidence

For each project, link to something real and checkable:
- **Excel**: a `.xlsx` file in a repo, or a Google Sheets view-only link
- **SQL**: a GitHub repo with your `.sql` files and a short README explaining the schema/problem
- **Power BI**: a published Power BI report link (Publish to web) or a screenshot gallery if the data is sensitive
- **Python**: a GitHub repo, ideally with a Jupyter notebook that renders on GitHub itself

Recruiters and hiring managers for senior roles will click through — having real, working links is what separates this from a template.

## 3. Deploy on GitHub Pages

1. Create a new repo, e.g. `yourusername.github.io` (for a root domain) or any repo name (for a project subpath).
2. Push these files:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/yourusername/your-repo.git
   git push -u origin main
   ```
3. In the repo, go to **Settings → Pages**.
4. Under **Source**, select the `main` branch and `/ (root)` folder, then Save.
5. Your site goes live at `https://yourusername.github.io/your-repo/` (or `https://yourusername.github.io/` if you used the special repo name).

## 4. Before you attach the link to your résumé

- Test on mobile — resize your browser or check on your phone
- Click every link on the live site once it's deployed
- Run it through Lighthouse (Chrome DevTools → Lighthouse) for a quick performance/accessibility check
- Double-check there's no leftover placeholder text (`Jordan Blake`, `[Your City]`, `yourusername`, etc.)
