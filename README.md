# FP&A Job Hunter

A personal job hunting app built for Sourabh Pandey — MBA-HHM, IIM Bodh Gaya.

Powered by **Apify** (LinkedIn scraping) and **Claude AI** (fit analysis + email drafting).

## Live app

👉 https://yourusername.github.io/fpa-job-hunter

*(Replace `yourusername` with your GitHub username after deployment)*

## Features

- **Job search** — scrape LinkedIn for FP&A and finance roles, auto-scored for profile fit
- **Live projects** — find short-term consulting and finance projects (LinkedIn, Unstop, Internshala, IIM network)
- **Recruiter finder** — search LinkedIn for HR and talent contacts at any company
- **Email composer** — Claude drafts personalised referral requests, cold intros, and project outreach emails

## Setup

1. Open the app in your browser
2. Go to the **Settings** tab
3. Paste your **Apify API token** (from apify.com → Settings → API & Integrations)
4. Paste your **Anthropic API key** (from console.anthropic.com → API Keys)
5. Click **Save keys** — keys are stored in your browser only, never sent anywhere else

## Tech

- Pure HTML + CSS + JavaScript — no framework, no build step
- Apify `curious_coder~linkedin-jobs-scraper` actor for LinkedIn data
- Claude `claude-sonnet-4-20250514` for fit scoring and email generation
- Keys stored in browser `localStorage`

## Security

API keys are **never** hardcoded in this repo. Always enter them via the Settings tab after opening the app.
