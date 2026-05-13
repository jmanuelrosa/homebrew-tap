<!-- Thanks for the PR. Most cask PRs only need a minute to fill in. -->

## Cask

<!-- Which cask is changing? e.g. `triage`. -->

## What changed

<!-- 1–2 lines. Common shapes:
- Bump `triage` to vX.Y.Z (release: https://github.com/jmanuelrosa/triage/releases/tag/vX.Y.Z)
- Add new cask `foo` from https://github.com/jmanuelrosa/foo
- Fix install / postflight for cask `triage`
-->

## Verification

- [ ] `sha256` matches the line for the corresponding artifact in the release's `SHA256SUMS.txt`
- [ ] `brew install --cask jmanuelrosa/tap/<cask>` succeeds on a clean machine
- [ ] `brew uninstall --cask <cask>` removes the app cleanly
- [ ] `brew style --fix --cask Casks/<cask>.rb` is happy (optional but recommended)

## Risk

<!-- What could break? Edge cases? "None — pure version bump" is fine for routine bumps. -->
