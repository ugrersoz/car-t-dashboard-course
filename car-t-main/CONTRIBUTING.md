# Contributing to the Recellion ImmunoReset Dashboard

Thanks for taking the time to look at this project. The dashboard is a **frozen academic deliverable** for the M9 Strategic Marketing in Life Sciences module at HTW Berlin, so the bar for contributions is "does this improve the demo or its documentation" — not full-scale product development.

## What we welcome

- Typo, grammar, and clarity fixes in `README.md` or `index.html`
- Accessibility improvements (semantic HTML, ARIA labels, colour contrast, keyboard navigation, focus states)
- Performance fixes (deferring scripts, reducing layout shift, image optimisation)
- Browser-compatibility bug reports
- Corrections or clarifications to the regulatory posture, SOSTAC® stage descriptions, or clinical references
- Documentation improvements — clearer setup steps, citation of sources, architecture notes

## What we won't merge

- Real clinical content, diagnostic logic, or anything implying clinical validity
- Backend integrations or stored patient data — this repo is a static demo by design
- Replacement of the submitted SOSTAC® analysis or marketing assumptions (the May 2025 deliverable is frozen)
- Large refactors or framework migrations (e.g. moving to React); those belong in the production roadmap, not the academic deliverable

## Workflow

1. **Open an issue first** for anything larger than a typo, so we can confirm the change fits the project scope.
2. Fork the repository and create a topic branch:
   ```bash
   git checkout -b fix/short-description
   ```
3. Make the change. Keep diffs small and focused.
4. Manually verify the demo still renders correctly:
   - Open `car-t-main/index.html` in Chrome / Firefox / Safari, or
   - Run `python -m http.server 8080` from `car-t-main/` and visit <http://localhost:8080>
   - Walk through every module: dashboard, screening, logistics, AE monitoring, insights, resources, SOSTAC®, cost calculator, treatment-process demo
5. Commit with a clear message (imperative mood, e.g. `Fix contrast on adverse-event severity badges`).
6. Open a pull request against `main` describing **what changed and why**, with a screenshot if the change is visual.

## Coding style

- **HTML / CSS / JS** live in one file by design. Don't split them out unless you're discussing a production refactor in an issue first.
- Two-space indentation, double quotes for HTML attributes.
- New custom CSS belongs inside the existing `<style>` block, near related rules.
- No new third-party CDN dependencies without prior discussion — Font Awesome is the only allowed runtime CDN today.
- Avoid inline event handlers (`onclick="..."`); attach listeners in the existing JS block.

## Reporting issues

Please include:

- Browser and version
- Steps to reproduce
- Expected vs. actual behaviour
- Screenshot or short screen capture if the issue is visual

## Code of conduct

Be kind, be specific, assume good faith. Disagreement on technical decisions is welcome; personal attacks are not.

## License

By contributing, you agree that your contributions are licensed under the [MIT License](../LICENSE) covering this repository.
