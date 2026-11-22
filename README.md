# Job Hunt Bot

A portable, shareable template for a job-search and application assistant — originally built as a Grok Bot by Rudraksh Syal, now platform-neutral so anyone can run it on Grok Bot, Muse, or another AI assistant.

**What it does**

- Finds fresh openings on LinkedIn, job boards, and company careers pages, and ranks them by fit and interview likelihood, linking every posting's own page
- Tailors your resume and cover letter for each role, using only your real achievements — never invented experience
- Applies on employer careers sites and ATS pages (never LinkedIn Easy Apply), at a human pace, only in a daytime submit window — nights are prep only
- Keeps a tracker of every job found and applied to, and opens every update with a running counter
- Watches your inbox for recruiter replies, interview invites, and rejections, and drafts replies for your review
- Never sends emails or messages without your OK — except standard post-application referral notes, if you pre-approve them as a class

**Files in this repo**

- `job_hunt_bot_template.md` — the full template: identity, core instructions, approval boundaries, the getting-started onboarding skill, all four routines (inbox watch + morning summary, nightly prep, daytime apply + outreach, A/B test comparison), connector setup, ranking criteria, resume-tailoring rules, application pace, and tracker fields. Replace every `[PLACEHOLDER]` with your own details before use.
- `job-hunt-playbook.md` — the same template, verified line by line, with an appendix on how each piece maps to Muse (routines to scheduled jobs, connectors to Gmail / Calendar / password vault, tracker to a structured file + dashboard).

**Getting started**

1. Copy `job_hunt_bot_template.md` into your AI assistant (or add the original on Grok Bot: https://x.ai/bot/axuGYabQcdSR4VAUeHcrU).
2. Run the getting-started conversation in the template — it asks for your resume, LinkedIn, target roles, salary floor, work authorization, companies to skip, and standing application answers, a few questions at a time.
3. Connect your email, calendar, LinkedIn (browser), and a password vault.
4. Fill in the placeholders, agree on which jobs the bot may apply to without asking, and start with one end-to-end test role before turning on daily volume.

**Privacy**

The template contains no one's personal data. Every personal value is a square-bracket placeholder, and the template itself instructs the bot to keep passwords only in a vault, never enter an SSN or date of birth, and keep street addresses out of memory, chat, and the tracker.

Created by Rudraksh Syal. Free to use and adapt — please keep the approval and honesty rules (never invent experience, never send without OK) intact.
