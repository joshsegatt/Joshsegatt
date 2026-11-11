<div align="center">

<img src="./assets/profile-hero.svg" width="100%" alt="Josh Segatt — software engineer building full-stack products, native applications and verifiable AI systems." />

<br />

**Independent software engineer** · Product systems · AI developer infrastructure

[**Explore engineering ↓**](#engineering-with-evidence) &nbsp; / &nbsp; [**See selected products ↓**](#selected-products) &nbsp; / &nbsp; [**Work together ↗**](#get-in-touch)

</div>

I'm **Josh**, a software engineer building full-stack applications, native tools, and infrastructure for AI-assisted development. I work from **product experience through architecture and implementation to verification**. The common thread: useful software, understandable systems, and claims backed by something you can inspect.

<img src="./assets/capability-strip.svg" width="100%" alt="Animated line icons for product interfaces, platform and data engineering, native software, and AI verification systems." />

## Engineering with evidence

### 01 — [SeniorOS](https://github.com/joshsegatt/SeniorOS) · Engineering infrastructure for coding agents

**The problem:** coding agents can write a patch and still miss the root cause, damage repository history, or report success without running the project's real checks.

**The approach:** modular skills and hooks, context-aware routing, explicit risk boundaries, verification gates, and a reproducible evaluation harness. The aim is not to make an agent *sound* more experienced. It's to make the workflow more **inspectable and reliable**.

**A measured result, with scope:** in a published fifth blind round of **three cause-elsewhere bug tasks × five trials on Claude Opus**, SeniorOS passed **10/15** runs versus **2/15** for the unassisted model. One task had an ambiguous expected product rule; no tested configuration passed it. These are results from this benchmark, **not a universal success rate**.

<div align="center">

<a href="https://github.com/joshsegatt/SeniorOS/blob/main/brand/social/proof.mp4">
  <img src="https://raw.githubusercontent.com/joshsegatt/SeniorOS/main/brand/social/proof.gif" width="94%" alt="Recorded side-by-side bug-fix comparison using Claude Sonnet 5.5: model alone and with SeniorOS. Click for the full video." />
</a>

<sub>Actual recorded runs, not a decorative animation. <a href="https://github.com/joshsegatt/SeniorOS/blob/main/brand/social/proof.mp4">Watch the 60-second comparison ↗</a></sub>

</div>

**Inspect the work:** [Source & architecture](https://github.com/joshsegatt/SeniorOS) · [Benchmarks, methodology & caveats](https://github.com/joshsegatt/SeniorOS/tree/main/evals/bench) · [Leaderboard](https://github.com/joshsegatt/SeniorOS/blob/main/evals/bench/LEADERBOARD.md)

### 02 — [chit](https://github.com/joshsegatt/chit) · A deterministic delivery gate

**The problem:** “tests pass” is a sentence. It isn't evidence that a patch fixed the reported regression.

**The approach:** run the specified test at `HEAD` in an isolated worktree and require a meaningful failure; run the **same test** after applying the patch and require success; independently replay both outcomes; generate a reviewable HTML receipt. A delivery verdict is withheld when the gates don't hold.

<img src="./assets/engineering-loop.svg" width="100%" alt="Animated verification diagram: red baseline at HEAD, green after patch, independent replay, and reviewable receipt." />

This proves that the specified test discriminates the baseline from the patch. **It does not prove that the test encodes the right product requirement.** The repository also distinguishes its scripted demos from unverified live IDE behavior.

**Inspect the work:** [Source, protocol & limitations](https://github.com/joshsegatt/chit) · [Example red/green evidence](https://github.com/joshsegatt/chit/blob/main/docs/redgreen.jpg)

---

## Selected products

Not every interesting engineering problem starts with AI. I also build products for operations, finance, desktop productivity, and gaming.

| Project | What it addresses | What I built with |
| :--- | :--- | :--- |
| **[Segatt Tools ↗](https://github.com/joshsegatt/Segatt-Tools)** | Local-first Windows maintenance and on-device assistance. | Tauri 2 · Rust · Next.js · WebLLM |
| **[Batimoving B2B ↗](https://github.com/joshsegatt/Batimoving-b2b)** | Moving and cleaning lead workflows for the Swiss market. | TypeScript · marketplace workflows · business rules |
| **[Finora ↗](https://github.com/joshsegatt/Finora)** | Offline Android expense tracking and receipt scanning. | Kotlin · Jetpack Compose · Room · ML Kit |
| **[Sable ↗](https://github.com/joshsegatt/Sable-Overlay-Gamer)** | Gaming telemetry and an in-game performance overlay (**beta**). | Rust · Tauri · Windows ETW · React |
| **[PriceCompass ↗](https://github.com/joshsegatt/PriceCompass)** | Organizing household bills and plan comparisons in the UK. | React · NestJS · PostgreSQL · Prisma |

<sub>More: <a href="https://github.com/joshsegatt/batimove.ch">Batimove</a> · <a href="https://github.com/joshsegatt/CVLetterAI">CVLetterAI</a> · <a href="https://github.com/joshsegatt/LabelGuardUK">LabelGuard UK</a> · <a href="https://github.com/joshsegatt/LocationMonteCharge.ch">Monte Charge</a> · <a href="https://github.com/joshsegatt/UK-TaxSaver">UK TaxSaver</a></sub>

## Engineering principles

**Start from the user.** Define the outcome, the constraints, and the things the change must *not* break.

**Treat architecture as a set of trade-offs.** Small boundaries, explicit states, and reversibility beat complexity added for appearance.

**Make verification repeatable.** Prefer observable behavior, failing baselines, real test commands, and artifacts another engineer can inspect.

**Be precise about limitations.** A benchmark is a benchmark. A beta is a beta. A passing test isn't proof of every requirement.

### Technical toolkit

<div align="center">

<img src="https://skillicons.dev/icons?i=ts,react,nextjs,nodejs,postgres,rust,python,kotlin,docker,githubactions&theme=dark&perline=10" alt="TypeScript, React, Next.js, Node.js, PostgreSQL, Rust, Python, Kotlin, Docker and GitHub Actions" />

</div>

**Web & API:** TypeScript, React, Next.js, Node.js, NestJS, PostgreSQL, Prisma / Drizzle.  
**Native:** Rust, Tauri, Kotlin, Jetpack Compose.  
**AI & engineering tools:** agent workflows, model integrations, local inference, evaluation and regression harnesses.  
**Delivery:** Docker, GitHub Actions, Vercel.

---

## Get in touch

I work at the intersection of **product engineering, native tooling, and AI developer infrastructure**. If you're reviewing my work as an engineer, start with the **[SeniorOS methodology](https://github.com/joshsegatt/SeniorOS/tree/main/evals/bench)** or **[chit's verification contract](https://github.com/joshsegatt/chit)**. If you're building a product and want to discuss a collaboration, here's the direct route:

<div align="center">

### [joshsegatt.com ↗](https://joshsegatt.com) &nbsp;·&nbsp; [Email me ↗](mailto:josuesegatofilho@gmail.com)

<sub>UK ↔ Switzerland · Remote collaboration</sub>

<br />

<sub>Design the product. Engineer the system. Show the evidence.</sub>

</div>
