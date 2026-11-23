<div align="center">

<img src="./assets/profile-hero.svg" width="100%" alt="Josh Segatt — software engineer building full-stack products, native applications and verifiable AI systems." />

<br />

**Software engineer** · Product systems · Native apps · AI developer infrastructure<br>
Co-founder of **[SG Tecnologia e Automações](https://github.com/sg-tecnologia-automacoes)**

[**Selected work**](#selected-work) &nbsp;·&nbsp; [**Evidence**](#evidence) &nbsp;·&nbsp; [**Principles**](#principles) &nbsp;·&nbsp; [**Contact**](#contact)

</div>

I take software from the product question to a verified release: what the person needs, the architecture that serves it, the implementation, and the evidence that it works. Web platforms, native apps for Windows, Android and iOS, and tooling that makes AI coding agents accountable.

<img src="./assets/capability-strip.svg" width="100%" alt="Animated line icons for product interfaces, platform and data engineering, native software, and AI verification systems." />

## Selected work

<a href="https://github.com/joshsegatt/SeniorOS"><img src="./assets/work-seniorOS.svg" width="100%" alt="SeniorOS: engineering infrastructure for coding agents. Blind round 5 on Claude Opus: 10 of 15 runs with SeniorOS, 2 of 15 for the model alone." /></a>
<sub>&nbsp;[Source](https://github.com/joshsegatt/SeniorOS) · [Methodology & caveats](https://github.com/joshsegatt/SeniorOS/tree/main/evals/bench) · [Leaderboard](https://github.com/joshsegatt/SeniorOS/blob/main/evals/bench/LEADERBOARD.md)</sub>

<a href="https://github.com/joshsegatt/chit"><img src="./assets/work-chit.svg" width="100%" alt="chit: a delivery gate. Red at HEAD, green after the patch, independent replay, reviewable receipt." /></a>
<sub>&nbsp;[Source, protocol & limitations](https://github.com/joshsegatt/chit) · [Example red/green evidence](https://github.com/joshsegatt/chit/blob/main/docs/redgreen.jpg)</sub>

<a href="https://github.com/joshsegatt/Segatt-Lab"><img src="./assets/work-segatt-lab.svg" width="100%" alt="Segatt Lab: open-source Windows 10 and 11 tuning, debloat, cleanup and repair, with live state and one-click undo." /></a>
<sub>&nbsp;[Download](https://github.com/joshsegatt/Segatt-Lab/releases/latest) · [Website](https://joshsegatt.github.io/Segatt-Lab/) · [Source](https://github.com/joshsegatt/Segatt-Lab)</sub>

<a href="https://github.com/joshsegatt/BatteryLife"><img src="./assets/work-batterylife.svg" width="100%" alt="BatteryLife: a Windows 11 tray hub that shows which wireless device to charge next and how long is left." /></a>
<sub>&nbsp;[Download](https://github.com/joshsegatt/BatteryLife/releases/latest) · [Source](https://github.com/joshsegatt/BatteryLife) · Device protocols from the community [BatteryHub](https://github.com/krisgfx9/Wireless-Device-Battery-Monitor) research</sub>

<a href="https://github.com/sg-tecnologia-automacoes"><img src="./assets/work-finora.svg" width="100%" alt="Finora: personal finance for Android, iOS next. Shows what is safe to spend this month; data stays on the phone." /></a>
<sub>&nbsp;Built with [SG Tecnologia e Automações](https://github.com/sg-tecnologia-automacoes) · Screens use demo data</sub>

<details>
<summary><b>More projects</b></summary>
<br>

| Project | What it addresses | Built with |
| :--- | :--- | :--- |
| **[Sable](https://github.com/joshsegatt/Sable-Overlay-Gamer)** | Gaming telemetry and an in-game performance overlay (beta). | Rust · Tauri · Windows ETW · React |
| **[PriceCompass](https://github.com/joshsegatt/PriceCompass)** | Household bills and plan comparisons in the UK. | React · NestJS · PostgreSQL · Prisma |
| **[Monte Charge](https://github.com/joshsegatt/LocationMonteCharge.ch)** | Desktop logistics hub for Swiss operations. | Tauri · Rust |
| **Batimoving B2B** | Moving and cleaning lead workflows for the Swiss market (private). | TypeScript |
| **[Batimove](https://github.com/joshsegatt/batimove.ch)** · **[CVLetterAI](https://github.com/joshsegatt/CVLetterAI)** · **[LabelGuard UK](https://github.com/joshsegatt/LabelGuardUK)** · **[UK TaxSaver](https://github.com/joshsegatt/UK-TaxSaver)** | Web products for Swiss and UK markets. | TypeScript · Next.js |

</details>

## Evidence

A claim about an agent is only as good as the run behind it. These are recorded, not staged.

<div align="center">

<a href="https://github.com/joshsegatt/SeniorOS/blob/main/brand/social/proof.mp4">
  <img src="https://raw.githubusercontent.com/joshsegatt/SeniorOS/main/brand/social/proof.gif" width="94%" alt="Recorded side-by-side bug-fix comparison using Claude Sonnet 5.5: model alone and with SeniorOS. Click for the full video." />
</a>

<sub>SeniorOS, recorded side by side. <a href="https://github.com/joshsegatt/SeniorOS/blob/main/brand/social/proof.mp4">Watch the 60-second comparison ↗</a></sub>

</div>

**Measured, with scope.** In the fifth blind round, 3 cause-elsewhere bug tasks × 5 trials on Claude Opus: **10/15** runs with SeniorOS, **2/15** for the model alone. One task had an ambiguous expected rule that no configuration passed. A benchmark result, not a universal success rate.

<img src="./assets/engineering-loop.svg" width="100%" alt="Animated verification diagram: red baseline at HEAD, green after patch, independent replay, and reviewable receipt." />

**What chit proves, and what it does not.** That the specified test separates the baseline from the patch. Not that the test encodes the right requirement.

## Principles

| | |
| :--- | :--- |
| **Start from the person** | Define the outcome, the constraints, and what the change must not break. |
| **Architecture is trade-offs** | Small boundaries, explicit states and reversibility beat complexity added for appearance. |
| **Verification is repeatable** | Failing baselines, real test commands, artifacts another engineer can inspect. |
| **Limits are stated** | A benchmark is a benchmark. A beta is a beta. A passing test is not every requirement. |

<div align="center">
<br>

<img src="https://skillicons.dev/icons?i=ts,react,nextjs,nodejs,postgres,rust,kotlin,flutter,dart,python,docker,githubactions&theme=dark&perline=12" alt="TypeScript, React, Next.js, Node.js, PostgreSQL, Rust, Kotlin, Flutter, Dart, Python, Docker and GitHub Actions" />

<sub><b>Web & API</b> TypeScript · React · Next.js · NestJS · PostgreSQL &nbsp;|&nbsp; <b>Native & mobile</b> Rust · Tauri · Kotlin Multiplatform · Compose · Flutter &nbsp;|&nbsp; <b>AI tooling</b> agent workflows · local inference · evaluation harnesses &nbsp;|&nbsp; <b>Delivery</b> GitHub Actions · Vercel · Google Play</sub>

</div>

## Contact

Reviewing my work as an engineer? Start with the **[SeniorOS methodology](https://github.com/joshsegatt/SeniorOS/tree/main/evals/bench)** or **[chit's verification contract](https://github.com/joshsegatt/chit)**.

<div align="center">

### [joshsegatt.com ↗](https://joshsegatt.com) &nbsp;·&nbsp; [Email me ↗](mailto:josuesegatofilho@gmail.com)

<sub>UK ↔ Switzerland · Remote collaboration</sub>

<br />

<sub>Design the product. Engineer the system. Show the evidence.</sub>

</div>
