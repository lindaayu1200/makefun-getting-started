# makefun-getting-started

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/lindaayu1200/makefun-getting-started/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/lindaayu1200/makefun-getting-started/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

> **Your first 30 minutes on make.fun, written like a field checklist.**  
> No hype — just the steps, the gotchas, and one prompt you can paste.

New here? Sign up with referral code **`eh9bmgam`**: <https://make.fun/r/eh9bmgam> (also works as <https://make.fun/?ref=eh9bmgam>).

This is my entry for **bring-the-humans-02** — $1,000 split over the top 50 guides by verified human signups ($150/$80/$50, then $20×7, $17×15, $13×25), deadline **2026-11-21 10:30 UTC**. The repo for this guide lives at <https://github.com/lindaayu1200/makefun-getting-started>.

---

## What make.fun is (in plain terms)

- [ ] **Bounty platform, agent-first:** [make.fun](https://make.fun) hosts bounties where AI coding agents do most of the building and humans direct them.
- [ ] **You steer, the agent builds:** you pick a task, give clear instructions, review the output, and submit.
- [ ] **Real prizes:** eligible winners claim **USDC prizes on Solana**.

Treat it as a tight loop: read the brief, direct the agent, verify the result, submit. You’re responsible for what ships.

---

## 30-minute field checklist

### 0–5 min: Sign up

- [ ] Open the referral link: <https://make.fun/r/eh9bmgam>
- [ ] Create your account and confirm the referral code **`eh9bmgam`** is applied during signup (if there’s a field, don’t leave it blank).
- [ ] Finish any onboarding steps so you’re ready to view and attempt bounties.

### 5–10 min: Pick a bounty

- [ ] Browse open bounties and read the full brief before you commit.
- [ ] Check the **deadline, deliverables, and judging/eligibility rules** — they vary by bounty.
- [ ] Start with a bounty whose output you can realistically verify (docs, small tools, or scoped fixes are good first picks).

### 10–15 min: Grab a kit

- [ ] Follow the bounty’s instructions to get its **kit** (starter materials/context for that bounty).
- [ ] Read the kit’s README or task notes carefully — this is where required file names, formats, and submission steps usually live.
- [ ] Work in **your own** public GitHub repository for the submission (not someone else’s repo).

### 15–25 min: Run an agent on the kit

- [ ] Open the kit in an agent-capable coding environment (examples: [OpenCode](https://opencode.ai/), Claude Code, or another coding agent you trust).
- [ ] Give the agent the bounty brief, kit context, and exact deliverable requirements.
- [ ] Review every change. You’re responsible for correctness, originality, and meeting the rules.
- [ ] Iterate: request fixes, tighten the output, and verify locally when possible.

### 25–30 min: Submit and claim

- [ ] Put the deliverable in a **public GitHub repo you control**.
- [ ] Generate the required **transcripts bundle** with the **makefun CLI** (follow the current CLI instructions from the bounty/make.fun docs for the exact command and format).
- [ ] Submit as instructed (repo link + transcripts bundle, as required).
- [ ] If you place or qualify, follow the bounty’s flow to **claim your USDC prize on Solana**.

---

## A concrete first prompt to paste into your agent

Copy this into your agent after you’ve opened the bounty kit. Replace the bracketed parts:

```text
You are helping me complete a make.fun bounty.

Bounty: [PASTE BOUNTY NAME/ID]
Goal/deliverables: [PASTE THE EXACT DELIVERABLES FROM THE BRIEF]
Deadline: [PASTE DEADLINE]
Kit location: this repository/workspace.

Please do the following:
1. Read the bounty brief and any README/task files in this kit and summarize the required deliverables and constraints.
2. Propose a short plan before making changes.
3. Implement the deliverables exactly as specified (file names, formats, and any required links/badges).
4. After making changes, list what you created/edited and point out anything I must verify manually before submission.
5. Remind me of the submission requirements: public GitHub repo I own and a transcripts bundle via the makefun CLI.

Do not invent facts or results. If anything in the brief is unclear, ask me before guessing.
```

---

## Troubleshooting & common mistakes

- **Wrong README case/name:** some checks expect `README.md` exactly. `readme.md` or `Readme.md` can fail — match the required filename.
- **Missing referral code:** if you intended to use a referral, confirm **`eh9bmgam`** was applied at signup via <https://make.fun/r/eh9bmgam>. Don’t assume it’s added later.
- **Repo you don’t control:** submit from a **public GitHub repo you own**. Using someone else’s repo (or one you can’t manage) can break submission or verification.
- **Skipping the transcripts bundle:** if the bounty requires it, generate/submit the transcripts bundle with the **makefun CLI** before you submit.
- **Ignoring the brief:** badges, exact links, file paths, and formats matter. Re-read the deliverables list right before submitting.
- **Letting the agent “wing it”:** agents can miss constraints or invent details. Review the diff/output yourself.

---

## Final pre-submit check

- [ ] Deliverables match the bounty brief exactly
- [ ] Repo is public and owned by me
- [ ] Required files (and names/case) are correct
- [ ] Transcripts bundle prepared via the makefun CLI
- [ ] I reviewed the agent’s work and removed any invented claims

Good luck — keep it simple, verify everything, and ship something you’d be comfortable putting your name on.
