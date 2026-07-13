# UniCORE.OpenClaw

        **SCAFFOLD-ANCHOR repository — initial commit 2026-06-05 18:51 UTC.**

        Full scaffolding, upstream-fork integration, and source-code work all pending a fresh dedicated kickoff arc. This initial commit exists to lock the repository's identity, licence position, and place in the UniCORE Sanity Check fleet so the work cannot be forgotten.

        Author: **Bryan Fred, Unitek Systems Limited, Bedford, United Kingdom.**
        First commit: **2026-06-05 18:51 UTC.**

        ---

        ## What this repository is

        `bryanunitek/UniCORE.OpenClaw` is the **OpenClaw** family member: On-prem-deployment-shape public gift surface. Documentation today; source code at certification.

        **Family purpose:** Personal AI assistant runtime + control plane. Multi-channel (WhatsApp / Telegram / Slack / Discord / Signal / iMessage / Teams / Matrix / and more), skills system, Canvas UI, native macOS / iOS / Android speech, gateway-managed installation. The substrate that powers MyClaw.ai.

        **Role in UniCORE:** AI-assistant runtime substrate — the building block on which Unitek's own Linux-server AI assistant (UnitekClaw Server, naming TBC) will be built. UniCORE.OpenClaw provides the runtime and channel surface; downstream Vertical-CORE Claws layer the Unitek brand, customer deployment configuration, and any private skill set on top.

        ---

        ## Upstream

        - **Upstream project:** [https://github.com/openclaw/openclaw](https://github.com/openclaw/openclaw)
        - **Upstream licence:** MIT
        - **Our relationship:** Fork-and-extend. Upstream codebase is consumed verbatim under its original licence; our additions sit on top under CC BY 4.0.

        **Our additions:** UniCORE.OpenClaw will add Unitek-authored skills, Vertical-CORE-aware integrations, branded Canvas surfaces, and any UniCORE-programme governance hooks (Nine-Invariants, attestation, sanity-check enrolment) that surface through the assistant runtime. All UniCORE-authored content ships CC BY 4.0 on top of the MIT base. Trademark "MyClaw" remains with OpenClaw Foundation; no UniCORE work uses that name.

        The merge discipline that governs how this repository absorbs upstream changes without losing UniCORE additions is documented in [`UPSTREAM-MERGE-DISCIPLINE.md`](UPSTREAM-MERGE-DISCIPLINE.md) at the root of this repository.

        ---

        ## Family — the four-repo pattern

        UniCORE.OpenClaw is published as a **four-repo family**:

        - `bryanunitek/UniCORE.OpenClaw` — public on-prem-deployment-shape gift surface
        - `bryanunitek/UniSaaS.UniCORE.OpenClaw` — public SaaS-deployment-shape gift surface
        - `bryanunitek/UniCORE.OpenClaw-Claw` (private) — on-prem-shape working repository
        - `bryanunitek/UniSaaS.UniCORE.OpenClaw-Claw` (private) — SaaS-shape working repository

        **This repository is the `UniCORE.OpenClaw` member of the family.**

        Sister repos:

        - [`UniSaaS.UniCORE.OpenClaw`](https://git.unitek-systems.com/UniCORE/UniSaaS.UniCORE.OpenClaw) (mirror: [GitHub](https://github.com/bryanunitek/UniSaaS.UniCORE.OpenClaw))
- `UniCORE.OpenClaw-Claw (private)`
- `UniSaaS.UniCORE.OpenClaw-Claw (private)`

        ---

        ## Status

        **SCAFFOLD-ANCHOR ONLY** as of 2026-06-05 18:51 UTC. See [`STATUS.md`](STATUS.md) for the full status breakdown and what is and is not in this initial commit.

        Bryan-authorised scope (2026-06-05 18:51 UTC):

        1. Fork MIT upstream into this repo (4 family members).
        2. Author CC BY 4.0 UniCORE-equivalent skills + integrations over the upstream base.
        3. Apply the canonical upstream-merge discipline.
        4. Enrol in UniCORE Sanity Check.

        This initial commit accomplishes (4) only. Items (1)–(3) follow in fresh dedicated arcs.

        ---

        ## Files in this initial commit

        - [`README.md`](README.md) — this file
        - [`LICENSE.md`](LICENSE.md) — CC BY 4.0 for UniCORE additions
        - [`LICENSE.upstream.md`](LICENSE.upstream.md) — verbatim copy of the upstream OSS licence
        - [`STATUS.md`](STATUS.md) — explicit scaffold-anchor status with what's pending
        - [`UPSTREAM-MERGE-DISCIPLINE.md`](UPSTREAM-MERGE-DISCIPLINE.md) — canonical merge discipline (applies once upstream is forked in)
        - `.gitignore`

        ---

        ## Related repositories — UniCORE programme

        **Foundation triad (gift, public, CC BY 4.0):**
        - [`UniVERSE`](https://git.unitek-systems.com/UniCORE/UniVERSE) (mirror: [GitHub](https://github.com/bryanunitek/UniVERSE)) — programme
        - [`TrueAI`](https://git.unitek-systems.com/UniCORE/TrueAI) (mirror: [GitHub](https://github.com/bryanunitek/TrueAI)) — Foundation (Nine Invariants)
        - [`UniCORE-AI`](https://git.unitek-systems.com/UniCORE/UniCORE-AI) (mirror: [GitHub](https://github.com/bryanunitek/UniCORE-AI)) — reference architecture (12 Levels)

        **Implementation reference (deployment-shape pair):**
        - [`UniCORE`](https://git.unitek-systems.com/UniCORE/UniCORE) (mirror: [GitHub](https://github.com/bryanunitek/UniCORE)) — on-prem-shape
        - [`UniSaaS.UniCORE`](https://git.unitek-systems.com/UniCORE/UniSaaS.UniCORE) (mirror: [GitHub](https://github.com/bryanunitek/UniSaaS.UniCORE)) — SaaS-shape

        **Substrate-services layer (deployment-shape pair):**
        - [`UniCORE.GVB`](https://git.unitek-systems.com/UniCORE/UniCORE.GVB) (mirror: [GitHub](https://github.com/bryanunitek/UniCORE.GVB)) — on-prem-shape
        - [`UniSaaS.UniCORE.GVB`](https://git.unitek-systems.com/UniCORE/UniSaaS.UniCORE.GVB) (mirror: [GitHub](https://github.com/bryanunitek/UniSaaS.UniCORE.GVB)) — SaaS-shape

        **Forked-upstream building blocks (this family + siblings):**
        - UniCORE.Avalonia family (4 repos)
        - UniCORE.DNN family (4 repos)
        - UniCORE.OpenClaw family (4 repos) — *this family*

        ---

        ## Contact

        - **Public discussion:** [GitHub Discussions](https://github.com/bryanunitek/UniCORE.OpenClaw/discussions) (public repos only)
        - **Private contact / connection request:** [LinkedIn — Bryan Fred](https://www.linkedin.com/in/bryan-fred-02209753/)

        ---

        *Author: Bryan Fred, Unitek Systems Limited, Bedford, United Kingdom. Public gift-surface repository.*
