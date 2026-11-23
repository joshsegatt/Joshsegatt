<div align="center">

<img src="./assets/profile-hero.svg" width="100%" alt="Josh Segatt — software engineer building full-stack products, native applications and verifiable AI systems." />

<br />

**Software engineer** · Product systems · Native apps · AI developer infrastructure<br>
Co-founder of **[SG Tecnologia e Automações](https://github.com/sg-tecnologia-automacoes)**

[**Engineering with evidence ↓**](#engineering-with-evidence) &nbsp; / &nbsp; [**Products ↓**](#products) &nbsp; / &nbsp; [**Get in touch ↓**](#get-in-touch)

</div>

I'm **Josh**. I take software from the product question to a verified release: what the person needs, the architecture that serves it, the implementation, and the evidence that it works. I build web platforms, native apps for Windows, Android and iOS, and tooling that makes AI coding agents accountable.

<img src="./assets/capability-strip.svg" width="100%" alt="Animated line icons for product interfaces, platform and data engineering, native software, and AI verification systems." />

## Engineering with evidence

### [SeniorOS](https://github.com/joshsegatt/SeniorOS) · Engineering infrastructure for coding agents

Coding agents can write a patch that misses the root cause, damages history, or reports success without running the project's checks. SeniorOS adds skills and hooks with risk boundaries, verification gates and a reproducible evaluation harness, so the workflow becomes **inspectable**, not just more confident.

**Measured, with scope:** in the fifth blind round (**3 cause-elsewhere bug tasks × 5 trials on Claude Opus**), SeniorOS passed **10/15** runs against **2/15** for the model alone. One task had an ambiguous expected rule that no configuration passed. A benchmark result, **not a universal success rate**.

<div align="center">

<a href="https://github.com/joshsegatt/SeniorOS/blob/main/brand/social/proof.mp4">
  <img src="https://raw.githubusercontent.com/joshsegatt/SeniorOS/main/brand/social/proof.gif" width="94%" alt="Recorded side-by-side bug-fix comparison using Claude Sonnet 5.5: model alone and with SeniorOS. Click for the full video." />
</a>

<sub>Recorded runs, not a decorative animation. <a href="https://github.com/joshsegatt/SeniorOS/blob/main/brand/social/proof.mp4">Watch the 60-second comparison ↗</a></sub>

</div>

[Source & architecture](https://github.com/joshsegatt/SeniorOS) · [Methodology & caveats](https://github.com/joshsegatt/SeniorOS/tree/main/evals/bench) · [Leaderboard](https://github.com/joshsegatt/SeniorOS/blob/main/evals/bench/LEADERBOARD.md)

### [chit](https://github.com/joshsegatt/chit) · A deterministic delivery gate

"Tests pass" is a sentence, not evidence. chit runs the specified test at `HEAD` in an isolated worktree and requires a meaningful failure, runs the **same test** after the patch and requires success, replays both independently, and writes a reviewable HTML receipt. No receipt, no delivery verdict.

<img src="./assets/engineering-loop.svg" width="100%" alt="Animated verification diagram: red baseline at HEAD, green after patch, independent replay, and reviewable receipt." />

It proves the test separates the baseline from the patch. **It does not prove the test encodes the right requirement.**
[Source, protocol & limitations](https://github.com/joshsegatt/chit) · [Example red/green evidence](https://github.com/joshsegatt/chit/blob/main/docs/redgreen.jpg)

---

## Products

### [Segatt Lab](https://github.com/joshsegatt/Segatt-Lab) · Windows, tuned and repaired in the open

Debloat, tweak, clean and repair Windows 10 and 11. Every tweak shows its live state before it changes anything, saves the original value, and is read back after writing, so one click undoes it. Bootable USB maker, winget apps, 10 languages, no telemetry.
`Tauri 2 · Rust · Next.js` · [Download](https://github.com/joshsegatt/Segatt-Lab/releases/latest) · [Website](https://joshsegatt.github.io/Segatt-Lab/)

### [Finora](https://github.com/sg-tecnologia-automacoes) · Personal finance, private by design

Shows at a glance what is still safe to spend this month and logs an expense in three taps. Data stays on the phone: no account, no server. Built with SG Tecnologia e Automações; in closed testing on Google Play, iOS next.
`Kotlin Multiplatform · Compose Multiplatform · Room`

### More

| Project | What it addresses | Built with |
| :--- | :--- | :--- |
| **[Sable ↗](https://github.com/joshsegatt/Sable-Overlay-Gamer)** | Gaming telemetry and an in-game performance overlay (**beta**). | Rust · Tauri · Windows ETW · React |
| **[PriceCompass ↗](https://github.com/joshsegatt/PriceCompass)** | Household bills and plan comparisons in the UK. | React · NestJS · PostgreSQL · Prisma |
| **Batimoving B2B** | Moving and cleaning lead workflows for the Swiss market (private). | TypeScript · marketplace workflows |
| **[Monte Charge ↗](https://github.com/joshsegatt/LocationMonteCharge.ch)** | Desktop logistics hub for Swiss operations. | Tauri · Rust |

<sub>Also: <a href="https://github.com/joshsegatt/batimove.ch">Batimove</a> · <a href="https://github.com/joshsegatt/CVLetterAI">CVLetterAI</a> · <a href="https://github.com/joshsegatt/LabelGuardUK">LabelGuard UK</a> · <a href="https://github.com/joshsegatt/UK-TaxSaver">UK TaxSaver</a></sub>

## Principles

**Start from the person.** Define the outcome, the constraints, and what the change must not break.<br>
**Architecture is trade-offs.** Small boundaries, explicit states and reversibility beat complexity added for appearance.<br>
**Verification is repeatable.** Failing baselines, real test commands, artifacts another engineer can inspect.<br>
**Limits are stated.** A benchmark is a benchmark. A beta is a beta. A passing test is not every requirement.

<div align="center">

<img src="https://skillicons.dev/icons?i=ts,react,nextjs,nodejs,postgres,rust,kotlin,flutter,dart,python,docker,githubactions&theme=dark&perline=12" alt="TypeScript, React, Next.js, Node.js, PostgreSQL, Rust, Kotlin, Flutter, Dart, Python, Docker and GitHub Actions" />

</div>

**Web & API:** TypeScript, React, Next.js, Node.js, NestJS, PostgreSQL, Prisma / Drizzle.<br>
**Native & mobile:** Rust, Tauri, Kotlin Multiplatform, Compose, Flutter, Dart.<br>
**AI tooling:** agent workflows, model integrations, local inference, evaluation and regression harnesses.<br>
**Delivery:** Docker, GitHub Actions, Vercel, Google Play.

---

## Get in touch

Reviewing my work as an engineer? Start with the **[SeniorOS methodology](https://github.com/joshsegatt/SeniorOS/tree/main/evals/bench)** or **[chit's verification contract](https://github.com/joshsegatt/chit)**. Building a product and want to talk:

<div align="center">

### [joshsegatt.com ↗](https://joshsegatt.com) &nbsp;·&nbsp; [Email me ↗](mailto:josuesegatofilho@gmail.com)

<sub>UK ↔ Switzerland · Remote collaboration</sub>

<br />

<sub>Design the product. Engineer the system. Show the evidence.</sub>

</div>
