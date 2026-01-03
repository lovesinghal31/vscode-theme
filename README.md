# Carbon Night (black-theme)

A pure-black VS Code theme with subtle borders and blue accents.

## Theme

- **Theme name in VS Code**: `Carbon Night`
- **Base**: `vs-dark`

## Highlights

- True black editor/workbench background (`#000000`)
- Stronger **Command Palette** background + clearer separation (Quick Input / Quick Pick)
- Improved **Copilot Chat / Inline Chat** styling (near-black inputs with subtle blue borders/shadows)
- Better code readability via **current-line highlight**, **line numbers**, and **indent guides**

## Install (Development)

This repository is a VS Code theme extension.

1. Open this folder in VS Code
2. Press `F5` to start an **Extension Development Host** window
3. In the new window, open the theme picker (`Ctrl+K Ctrl+T`) and select `Carbon Night`

Changes to `themes/Carbon Night-color-theme.json` apply automatically in the dev host.

## Recommended Settings

This theme includes indent guide colors, but VS Code needs the guides enabled:

```json
{
  "editor.guides.indentation": true,
  "editor.guides.highlightActiveIndentation": true
}
```

## Files

- Theme definition: `themes/Carbon Night-color-theme.json`
- Extension manifest: `package.json`
- Change log: `CHANGELOG.md`
