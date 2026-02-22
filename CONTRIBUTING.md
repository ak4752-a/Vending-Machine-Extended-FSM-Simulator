# Contributing to Vending Machine Extended FSM Simulator

Thank you for your interest in contributing! This is a simple static web project — no build system or package manager is required.

---

## Reporting Bugs

1. Check the [existing issues](../../issues) to avoid duplicates.
2. Open a new issue with:
   - A clear title describing the problem.
   - Steps to reproduce (which buttons you clicked, in what order).
   - Expected vs. actual behavior.
   - Browser and OS version.

---

## Suggesting Improvements

Open an issue labelled **enhancement** and describe:

- What you'd like to see added or changed.
- Why it would improve the simulator.
- Any relevant FSM concepts it would demonstrate.

---

## Making Code Changes

1. **Fork** the repository and create a branch from `main`.
2. Make your changes in `index.html` (and `screenshots/` if adding images).
3. Test locally by opening `index.html` in a browser, or run a local server:
   ```bash
   python -m http.server 8080
   # Then open http://localhost:8080
   ```
4. Verify the app works with no console errors.
5. Open a **Pull Request** against `main` with a clear description of your change.

---

## Code Style

- Keep everything in plain HTML / CSS / vanilla JavaScript — no frameworks or build steps.
- Follow the existing indentation (4-space) and naming conventions.
- Add comments only where the logic is non-obvious.

---

## Adding Screenshots

Place new screenshots in the `screenshots/` folder:

- Recommended size: **~1280×720 px**
- Filename: **lowercase with hyphens** (e.g., `my-feature.png`)
- Format: **PNG** preferred for UI screenshots
- Keep file sizes reasonable — compress images above ~500 KB before committing.

Then reference them in `README.md` with a relative link:

```markdown
![Description](screenshots/my-feature.png)
```
