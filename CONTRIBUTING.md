# Contributing

Thank you for helping improve Enhanced Biofects for Jellyfin.

## Before You Start

- Search existing issues before opening a new one.
- Use the bug form for regressions and compatibility problems.
- Use the feature form for visual or behavior proposals.
- Report suspected vulnerabilities privately as described in `SECURITY.md`.

## Development

1. Fork the repository and create a focused branch from `main`.
2. Make the smallest CSS change that solves the issue.
3. Test with Jellyfin Web 10.11 or newer using only this theme's CSS.
4. Check the affected view at desktop and mobile widths.
5. Confirm dialogs, playback controls, focus states, and text remain usable.
6. Run `git diff --check` before submitting.

Keep selectors scoped to the affected Jellyfin component. Reuse the custom
properties near the top of `Enhanced-Biofects-Jellyfin.css` instead of adding
one-off colors or effects when an existing token fits.

## Pull Requests

Include:

- A concise description of the problem and solution
- The Jellyfin server and web-client versions tested
- Before and after screenshots for visible changes
- Any known limitations or selectors likely to vary by Jellyfin version

By submitting a contribution, you agree that it may be distributed under the
MIT License. All participation is governed by the Code of Conduct.
