# Contributing

Contributions and issue reports are welcome.

For color or syntax changes, please preserve the theme's existing semantic palette and visual hierarchy. Changes to token scopes should ideally be supported by output from **Developer: Inspect Editor Tokens and Scopes** in Visual Studio Code.

Before opening a pull request:

1. Test the theme in an Extension Development Host.
2. Verify affected languages with token inspection where appropriate.
3. Run `npm run verify`.
4. Build the extension with `npm run package`.
5. Update `CHANGELOG.md` for user-visible changes.
