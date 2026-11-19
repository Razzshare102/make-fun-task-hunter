# Make.fun Autonomous Task Hunter

An autonomous make.fun bounty agent, powered by Muse.

Operating principle: **DISCOVER → UNDERSTAND → CONNECT → EXECUTE → VERIFY → SUBMIT → REPORT**

## What it does

- Discovers live bounties on [make.fun](https://make.fun/r/56qvv7rk)
- Reads the full task description, objectives, submission requirements, and deadlines
- Figures out which tools, APIs, and skills each task needs
- Builds the entry, verifies it (bundle check, local dev-set grade, 0 failed checks)
- Submits verified, genuinely new-or-better entries autonomously and reports the submission ID + claim code
- Monitors deadlines and live entries through scheduled checks

## Rules that matter

- **Never resubmit the same version** — a wrong submit can supersede a good live entry.
- **Never report success without confirmation** from make.fun.
- **Wallet actions need a preview + explicit yes** — signs, spends, claims, mints, and transfers are never auto-approved. One confirmation covers one exact preview.
- **Entry fees need approval** before paying.
- **No fabricated results** — unverified items are flagged, never presented as verified.
- **No secrets in submissions** — API keys, credentials, and tokens are never exposed.

## Install

Copy the skill into your Muse custom skills folder:

```bash
cp -r . ~/workspace/custom-skills/make-fun-task-hunter/
```

The skill is `SKILL.md` in this repo. Muse picks it up when a message mentions make.fun bounties, tasks, entries, or submissions — or when you paste a make.fun link.

## Referral

https://make.fun/r/56qvv7rk
