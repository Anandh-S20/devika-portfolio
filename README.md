# Devika C S — Portfolio Website

Personal portfolio website of **Devika C S**, Aspiring Data Analyst, built with Next.js and Tailwind CSS. Dark, responsive, recruiter-friendly single-page site with Hero, About, Experience, Projects, Skills, Education & Certifications, and Contact sections.

## Tech Stack

- Next.js 16 (App Router)
- React 19 + TypeScript
- Tailwind CSS v4
- Deployed on Vercel

## Run Locally

```bash
npm install
npm run dev
```

Open http://localhost:3000 in your browser.

## Build for Production

```bash
npm run build
npm run start
```

## Customize the Content

All portfolio content lives in one file: `src/data/portfolio.ts`. Edit the name, headline, experience, projects, skills, education, certifications, and contact details there — no other files need to change. Components read from this file automatically.

## Deploy

1. Create a new GitHub repository named `devika-portfolio` and push this project:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/<your-username>/devika-portfolio.git
   git push -u origin main
   ```
2. On [Vercel](https://vercel.com), click **New Project** → import the `devika-portfolio` repository → Deploy (no extra configuration needed).

## Suggested Repository Name

`devika-portfolio`
