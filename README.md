# Steady 🌿

**A calm toolkit for learners — created with care for Domonique.**

Steady is a free, accessible, privacy-minded toolkit for feelings, visual routines, communication, sensory breaks and inclusive learning plans. No paid API, login or dependency installation required.

## What's included

- **Feelings:** untimed emotion-matching practice and a check-in that isn't saved.
- **My day:** editable visual routine, progress tracking, reordering and reset.
- **Talk board:** customizable messages, a large display, device speech where supported.
- **Calm space:** opt-in breathing visual, optional timer and grounding prompts.
- **Lesson planner:** age-aware learning outline, exact-length schedule, edit, print and export.
- **Settings:** dark/light display, larger text, reduced motion, speech settings, and backup or erase.

## Open the application

Open the repository's [index.html](./index.html). It contains the complete app, including its styling and behavior. For a public website, enable GitHub Pages below. `sw.js` enables basic offline caching after a successful visit over HTTPS.

## Publish via GitHub Pages

The repository is **private** as initially created. GitHub Pages is free for **public repositories** on the GitHub Free personal plan; private-repo availability depends on the plan. Do not add private learner data to this repository.

1. If a public site is acceptable, switch repository visibility to **Public** in **Settings → General → Danger Zone**.
2. Open **Settings → Pages → Build and deployment**, enable GitHub Pages and choose **GitHub Actions**. This administrative setup cannot be performed by the workflow token (GitHub rejects it with `Resource not accessible by integration`).
3. Open **Settings → Secrets and variables → Actions → Variables** and create the repository variable **`STEADY_PAGES_ENABLED`** with value **`true`**. Until that is set, automatic deployment checks intentionally skip instead of failing every push.
4. Open **Actions → Publish Steady to GitHub Pages** and run the workflow, or push another commit.
5. Once a deployment succeeds, the site should be at **https://deaconjason-stack.github.io/steady/**.

Publishing is **not** confirmed until GitHub Pages shows a successful deployment. GitHub Pages provides static hosting, not online user accounts or data synchronization.

## Privacy and safety

Steady has no tracking, analytics or backend. Saved schedules and phrases stay in the browser's local storage and can be backed up or erased. On shared devices, other people using the same browser profile may be able to see them; clearing browser data may erase them. Backups can contain private information.

Steady is a learning and communication **support**, not a medical device, diagnostic service, emergency support, or replacement for individually assessed communication tools. Conduct real learner testing, accessibility review and appropriate educator/professional evaluation before institutional use. Text-to-speech varies by device, browser and installed voice.

## Source files

The companion **Steady 2.0 Enhanced GitHub Ready** ZIP also contains the modular source code, optional install icons and smoke tests. The web-hosted `index.html` here is a self-contained version so GitHub deployment is easy.
