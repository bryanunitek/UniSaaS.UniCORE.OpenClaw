# STATUS — UniCORE.OpenClaw

**Repository state as of 2026-06-05 18:51 UTC.**

---

## Scaffold-anchor only

This repository exists as a **scaffold anchor**. Its purpose at this moment is to:

1. Reserve the canonical name on `bryanunitek/`.
2. Lock the licence position (CC BY 4.0 for UniCORE additions over MIT upstream base).
3. Document the family pattern and upstream relationship in [`README.md`](README.md).
4. Document the merge discipline that will govern future upstream absorptions in [`UPSTREAM-MERGE-DISCIPLINE.md`](UPSTREAM-MERGE-DISCIPLINE.md).
5. Enrol the repository in the **UniCORE Sanity Check fleet** so it cannot be forgotten.

Nothing else is in this initial commit. Specifically:

- **No upstream fork yet.** The upstream codebase (https://github.com/openclaw/openclaw, MIT-licensed) has NOT been merged into this repository yet.
- **No UniCORE additions yet.** No source code, no skills, no integrations.
- **No solution / project structure.**
- **No CI configuration.**

---

## What is queued

Per Bryan-authorised scope (2026-06-05 18:51 UTC):

1. **Fork the upstream codebase** into this repository's `main` branch using the `git remote add upstream` + `git fetch upstream` + `git push origin main` pattern.
2. **Create the `unicore` branch** off `main`. All UniCORE additions land on `unicore`.
3. **Author UniCORE-authored content** — skills, integrations, governance hooks, branded Canvas surfaces — under appropriately-named directories per the upstream-merge discipline document.
4. **Apply the merge cadence** — per upstream release or weekly fallback.
5. **Test fence** before every push to `unicore`.

---

## What this initial commit DOES guarantee

- The repository will be picked up by the next **UniCORE Sanity Check** automatically.
- The licence boundary is documented before any upstream code lands.
- The merge discipline is canonical and reusable — same discipline document applies to every UniCORE family that forks an upstream OSS codebase.
- The four-repo family pattern is locked: `<Name>` (public on-prem) + `UniSaaS.<Name>` (public SaaS) + `<Name>-Claw` (private on-prem working) + `UniSaaS.<Name>-Claw` (private SaaS working).

---

## What this initial commit DOES NOT guarantee

- **No timeline for the upstream fork.** The fork happens in a dedicated kickoff arc; that arc is queued, not scheduled.
- **No feature parity claim.** Until UniCORE additions are authored, this repo cannot be advertised as "MyClaw-equivalent" or "OpenClaw-with-Unitek-skills". It is a scaffold-anchor only.
- **No certification readiness.** Certification readiness applies to Vertical COREs built on UniCORE substrate; this repo is a substrate building-block, not a Vertical CORE.

---

## Trademark note

The brand name "MyClaw" is OpenClaw Foundation's product name and is **not** used in this repository or any UniCORE family. UniCORE.OpenClaw consumes the OpenClaw runtime as a substrate; the downstream Unitek-branded assistant server uses Unitek branding (final naming TBC, candidates: "UnitekClaw Server").

---

## How to verify this repository's role in the family

```bash
# Confirm the four-repo family exists on GitHub
git ls-remote git@github.com:bryanunitek/UniCORE.OpenClaw.git HEAD
git ls-remote git@github.com:bryanunitek/UniSaaS.UniCORE.OpenClaw.git HEAD
git ls-remote git@github.com:bryanunitek/UniCORE.OpenClaw-Claw.git HEAD
git ls-remote git@github.com:bryanunitek/UniSaaS.UniCORE.OpenClaw-Claw.git HEAD
```

All four should return a HEAD ref. If any returns nothing, the family is incomplete and the missing member needs to be created on GitHub before the kickoff arc can run.

---

## Next actions

| When | Action | Owner |
|---|---|---|
| Pending Bryan kickoff signal | Schedule the UniCORE.OpenClaw fresh dedicated 24h arc | Bryan |
| Inside that arc | Fork upstream into this repository's `main` | main Claw |
| Inside that arc | Create `unicore` branch + author first UniCORE addition | main Claw |
| Inside that arc | Full scaffolding pass (READMEs / ROADMAPs / STATEMENT-ON-CLAIMS / AGENTS) | main Claw |
| After that arc | Update this STATUS.md to reflect the new repository state | main Claw |

---

*Status owned by: main Claw. Reviewed by: Bryan Fred.*
