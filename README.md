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

## Make Steady open as a real website

**GitHub files are not themselves a public website.** Clicking `index.html` in the repository opens code, not the app.

The repository was initially created **private**. On **GitHub Free**, Pages is available only for **public** repositories; on GitHub Pro and some higher plans, private repositories can also publish Pages.

### Fastest no-cost option (make the code public)
1. Review the code to make sure it contains no secrets or private learner information.
2. Go to **Settings → General → Danger Zone → Change repository visibility → Public**. This makes source code publicly viewable.
3. Go to **Settings → Pages → Build and deployment → Source: GitHub Actions**.
4. Go to **Actions → Publish Steady to GitHub Pages → Run workflow**, selecting `main` if prompted.
5. When **Actions** displays a successful deployment, open **https://deaconjason-stack.github.io/steady/** in Chrome or another browser.

The publication workflow now runs automatically for public repositories; **no repository variable is required**.

### If you want the source to remain private
Keep the repository private. Pages publishing then requires an eligible GitHub plan. If Pages is enabled for your private repository, create the Actions variable `STEADY_PAGES_ENABLED` with value `true` and manually run the workflow. The resulting Pages website is generally still public, even when the source repository is private.

### Android / mobile
A downloaded `.html` preview may be blocked by some chat or file-viewer apps. Save the enhanced project ZIP to Downloads, extract it with the Android Files app, then open `index.html` with Chrome. The hosted website link above is easier once publication succeeds.

Publishing is **not** confirmed until GitHub Actions reports a successful Pages deployment. GitHub Pages provides static hosting, not online user accounts or data synchronization.

## Privacy and safety

Steady has no tracking, analytics or backend. Saved schedules and phrases stay in the browser's local storage and can be backed up or erased. On shared devices, other people using the same browser profile may be able to see them; clearing browser data may erase them. Backups can contain private information.

Steady is a learning and communication **support**, not a medical device, diagnostic service, emergency support, or replacement for individually assessed communication tools. Conduct real learner testing, accessibility review and appropriate educator/professional evaluation before institutional use. Text-to-speech varies by device, browser and installed voice.

## Source files

The companion **Steady 2.0 Enhanced GitHub Ready** ZIP also contains the modular source code, optional install icons and smoke tests. The web-hosted `index.html` here is a self-contained version so GitHub deployment is easy.
