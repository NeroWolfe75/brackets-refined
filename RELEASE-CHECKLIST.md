# First Release Checklist

## Repository

- [ ] Create the public GitHub repository `NeroWolfe75/brackets-refined`.
- [ ] Upload/commit the complete project to the `main` branch.
- [ ] Confirm that GitHub Issues are enabled.

## Marketplace publisher

- [ ] Create or confirm the Visual Studio Marketplace Publisher ID `NeroWolfe`.
- [ ] Confirm that `publisher` in `package.json` exactly matches the Marketplace Publisher ID.

## Final validation

- [ ] Open the repository in Visual Studio Code and press `F5`.
- [ ] Select **Brackets Refined** in the Extension Development Host.
- [ ] Perform a visual smoke test in Python and TypeScript/JavaScript.
- [ ] Run `npm run verify`.
- [ ] Run `npm run package`.
- [ ] Install `brackets-refined-1.0.0.vsix` locally and perform one final smoke test.

## GitHub release

- [ ] Commit all final changes.
- [ ] Push the `main` branch.
- [ ] Create and push tag `v1.0.0`.
- [ ] Confirm that the GitHub Actions release workflow succeeds.
- [ ] Confirm that GitHub Release `v1.0.0` contains the generated VSIX.

## Visual Studio Marketplace

- [ ] Authenticate `vsce` with the `NeroWolfe` publisher.
- [ ] Publish version `1.0.0` after the GitHub release has been validated.
