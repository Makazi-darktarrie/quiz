# Project Guidance

- `index.html` is the source of truth for this offline, dependency-free quiz. Keep its styles and script inline; do not add a framework, package manager, or server unless requested.
- `quIZ.HTML` is an empty legacy file, not a second app entry point. Do not duplicate or move the quiz there unless explicitly asked.
- Preserve the quiz flow and state: 10 questions, score, progress, answer feedback, results, and replay.
- Keep controls keyboard-operable with visible focus. Preserve semantic labels, live feedback, progress-bar values, and reduced-motion support.
- Preserve both `prefers-color-scheme` themes. When changing colors, update the shared CSS variables in both palette blocks and check readable contrast.
- Validate changes by opening `index.html` directly in the integrated browser. Smoke-test keyboard answer selection, correct and incorrect feedback, score/progress changes, results, and replay. There is no build step or dependency-based test suite.
