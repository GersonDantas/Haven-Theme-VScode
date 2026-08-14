# Changelog

## Unreleased

- Gave the JavaScript and TypeScript `this` receiver a dedicated warm-violet accent in Haven Light and Dark, separating contextual access from ordinary variables.
- Increased the vibrancy of reserved words and gave class names a dedicated cobalt-blue accent, distinguishing classes from interfaces and other types.

## 1.1.3

- Reduced the visual weight of the editor gutter's add-comment button and comment range indicator in both Haven variants, keeping code as the primary focus.
- Made information-diagnostic backgrounds transparent in both variants, so spelling issues retain their underline without placing colored blocks behind the text.

## 1.1.2

- Increased text-selection opacity in both Haven variants.
- Corrected the native VS Code Source Control Graph through its supported `scmGraph.*` tokens, giving local references a blue background, remote references a warm purple background, base references an ochre background, and every label a high-contrast foreground.
- Completed the GitLens 19 Commit Graph palette with all ten lanes and every registered graph marker. HEAD and local branches use blue, upstream and remote branches use purple, pull requests use purple, tags use ochre, stashes use pink, worktrees and WIP use orange, additions use green, and deletions use red.
- Avoided unsupported GitLens reference-background, reference-foreground, and pull-request-status token names that would be silently ignored by the installed extension.
- Separated the editor canvas subtly from the surrounding workbench in both variants while keeping the gutter, line-number area, sticky scroll, and minimap nearly continuous with the editor surface.
- Increased syntax vibrancy and base-text clarity in both variants while keeping comments and supporting interface text visually quieter.

## 1.1.0

- Added automatic VS Code defaults for system appearance detection and the preferred Haven Light and Dark themes, without overwriting explicit user settings.
- Increased text-selection density and inactive-selection visibility in the Light and Dark themes.
- Added explicit GitLens HEAD marker colors so current-branch pills remain visible in both variants.

## 1.0.0

This is a major visual release for Haven. It is more than a palette refresh: the new `Haven Light` and `Haven Dark` themes introduce a complete workbench color system alongside the existing warm solid variants, with coverage for the current VS Code theme tokens and semantic highlighting.

- Reworked the visual hierarchy so the editor and syntax remain the focus while panels, buttons, borders, and inactive UI recede.
- Increased syntax color vibrancy in both variants while preserving comfortable contrast for long coding sessions.
- Tuned Light backgrounds toward a subtle warm Solarized-like cream and Dark backgrounds toward a restrained amber-charcoal tone.
- Clarified change semantics: current merge changes use green, incoming changes use red, and unresolved conflicts use a separate Haven orange.
- Made diff, minimap, and scrollbar overlays translucent enough to keep change markers visible during focus, hover, and scrolling.
- Added the complete Light and Dark theme files without removing `Haven Warm Light Solid` or `Haven Warm Dark Solid`, so the variants can coexist.

The release is considered major because it changes the theme architecture and the day-to-day reading experience across the editor, workbench, merge editor, diff editor, minimap, and scrollbar, rather than changing an isolated token or a single component.

## 0.16.0

- Aligned the dark theme's primary and inactive text contrast.
- Set modified editor tabs to orange accent in focused and unfocused states.

## 0.15.0

- Update icon image to better image.

## 0.14.0

- Refreshed the published screenshots for the current Haven preview.
- Bumped the extension release package to the latest tagged version.

## 0.13.0

- Refined diff editor colors for added and removed lines.
- Updated Git decoration colors to better match the current Haven palette.

## 0.12.0

- Added automatic light and dark theme switching guidance to the README.
- Documented the recommended VS Code color scheme settings for Haven.
- Added macOS, Windows, and Linux suggestions for sunset-driven theme switching.

## 0.11.0

- Refined light and dark syntax highlighting for `const` and other readonly symbols.
- Kept `this`, booleans, and `console` aligned to the same accent treatment.
- Improved bracket, brace, and parenthesis contrast in both variants.
- Aligned light-theme string quotes with string coloring for better readability.

## 0.10.0

- Adjusted light and dark syntax colors so string quotes follow the main text color.
- Aligned booleans and `console` with the same accent used for `this`.
- Updated bracket, brace, and parenthesis scopes to use the high-contrast foreground color.

## 0.9.0

- Updated repository, homepage, and issue tracker links to the dedicated VS Code repository.
- Refined the Marketplace presentation with the Haven extension icon and a simplified public README.
- Kept the packaged extension focused on the two published VS Code theme variants.

## 0.8.0

- Updated extension metadata to use the dedicated VS Code repository.
- Added the Haven extension icon to the published package.
- Simplified the package to ship only the generated VS Code theme files.
- Refined the Marketplace README to focus on the theme collection and screenshots.

## 0.7.0

- Separated the VS Code extension project from the original Zed theme project.
- Added initial Marketplace packaging and publisher metadata for Visual Studio Code.

## 0.6.0

- Added the initial Visual Studio Code theme extension scaffold.
- Ported `Haven Warm Dark Solid` and `Haven Warm Light Solid` from the Zed source.
- Added the initial packaged VS Code theme files for the two selected variants.
