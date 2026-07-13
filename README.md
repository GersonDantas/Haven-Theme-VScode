# Haven

Haven is a comfort-focused theme collection for Visual Studio Code, inspired by Dracula but shaped around a softer day-to-night editing experience.

## Background

This started as a personal customization of the Dracula themes I was using while refining colors, contrast, editor surfaces, active states, and syntax tones. Over time, the goal shifted from "another Dracula variant" to a theme collection centered on visual comfort.

During that process I started using a light theme again during the day. That pushed the work toward palettes that felt comfortable in both light and dark environments instead of treating the light side as an afterthought. The name Haven comes from that direction: a set of themes meant to feel like a visual refuge while coding.

## Included Themes

- `Haven Warm Dark Solid`
- `Haven Warm Light Solid`

## How It Differs From Dracula Variants

Haven keeps Dracula as an inspiration, but it is not intended to be a direct port of the original palette. This Visual Studio Code edition starts with the warm dark and warm light solid variants.

The main difference is the focus on comfort across a full day of use. Backgrounds, surfaces, selected states, line highlights, terminal colors, and muted text were tuned to reduce harsh contrast while keeping code readable.

## Automatic Light And Dark Setup

If you want Visual Studio Code to switch Haven automatically with the system appearance, this is the recommended setup:

```json
{
  "window.autoDetectColorScheme": true,
  "workbench.preferredLightColorTheme": "Haven Warm Light Solid",
  "workbench.preferredDarkColorTheme": "Haven Warm Dark Solid"
}
```

This tells VS Code to use the light theme when the system is in light mode and the dark theme when the system is in dark mode.

Suggested system setup:

- macOS: open `System Settings > Appearance` and choose `Auto`. This is how I do it on my Mac.
- Windows: use a tool such as Auto Dark Mode, or schedule a system/theme switch with Task Scheduler to follow sunrise and sunset.
- Linux: if your desktop environment supports automatic appearance switching, use that. On GNOME/Ubuntu, a night-theme switcher extension or a small scheduled script is usually the practical option.

This is a suggestion, not a requirement. You can keep Haven manual and switch themes yourself if you prefer.

## Screenshots

### Haven Warm Dark Solid

![Haven Warm Dark Solid](./screenshots/haven_warm_dark_solid.png)

### Haven Warm Light Solid

![Haven Warm Light Solid](./screenshots/haven_warm_light_solid.png)

## Contents

- `package.json`: extension metadata
- `themes/`: Visual Studio Code theme definitions
- `screenshots/`: theme screenshots
- `assets/`: extension icon and visual assets

## Author

Gerson Dantas
