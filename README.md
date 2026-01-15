# Onyx Theme Color & Experience

> A super-dark, minimal VS Code theme designed for focus and clarity

Onyx Experience delivers a distraction-free coding environment with deep black backgrounds, subtle borders, and carefully balanced syntax colors. Perfect for developers who prefer a clean, elegant workspace.

<p align="center"><img src="https://i.imgur.com/s9fnTrn.jpeg" alt="Onyx Theme Preview" width="100%"></p>

---

## Installation

1. Open **Extensions** in VS Code (`Ctrl+Shift+X` / `Cmd+Shift+X`)
2. Search for **"Onyx Theme Color & Experience"**
3. Click **Install**
4. When prompted, click **Install** to add the recommended icon themes
5. **Activate the complete experience:**
   - Color Theme: `Ctrl+K Ctrl+T` → Select **Onyx Theme Color & Experience**
   - File Icons: `Ctrl+Shift+P` → *"File Icon Theme"* → Select **Icons**
   - Product Icons: `Ctrl+Shift+P` → *"Product Icon Theme"* → Select **Feather**

---

## Features

**Ultra-Dark Palette** — Pure black backgrounds (#101010, #121212) reduce eye strain during extended sessions

**Minimal Visual Noise** — Subtle borders and muted accents keep your attention on the code

**Complete Icon Integration** — Bundled with carefully selected file and product icons

**Semantic Syntax** — Enhanced highlighting for modern JavaScript, TypeScript, Python, and more

---

## Recommended Settings

For the optimal experience, add these to your IDE `settings.json`:

```jsonc
{
  // ═══════════════════════════════════════════════════════════
  // THEME & APPEARANCE
  // ═══════════════════════════════════════════════════════════
  "workbench.colorTheme": "Onyx Theme Color & Experience",
  "workbench.iconTheme": "icons",
  "workbench.productIconTheme": "feather-vscode",

  // ═══════════════════════════════════════════════════════════
  // EDITOR - TYPOGRAPHY
  // ═══════════════════════════════════════════════════════════
  "editor.fontFamily": "JetBrains Mono, monospace",
  "editor.fontSize": 13,
  "editor.lineHeight": 1.45,
  "editor.fontLigatures": true,

  // ═══════════════════════════════════════════════════════════
  // EDITOR - CURSOR & ANIMATION
  // ═══════════════════════════════════════════════════════════
  "editor.cursorStyle": "line",
  "editor.cursorBlinking": "smooth",
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.cursorSurroundingLines": 8,

  // ═══════════════════════════════════════════════════════════
  // EDITOR - SCROLLING & NAVIGATION
  // ═══════════════════════════════════════════════════════════
  "editor.scrollbar.vertical": "hidden",
  "editor.scrollbar.horizontal": "hidden",
  "editor.smoothScrolling": true,
  "editor.fastScrollSensitivity": 5,
  "editor.mouseWheelZoom": true,

  // ═══════════════════════════════════════════════════════════
  // EDITOR - DISPLAY & RENDERING
  // ═══════════════════════════════════════════════════════════
  "editor.renderLineHighlight": "gutter",
  "editor.renderWhitespace": "none",
  "editor.wordWrap": "on",
  "editor.glyphMargin": false,

  // ═══════════════════════════════════════════════════════════
  // EDITOR - MINIMAP
  // ═══════════════════════════════════════════════════════════
  "editor.minimap.enabled": true,
  "editor.minimap.maxColumn": 100,

  // ═══════════════════════════════════════════════════════════
  // EDITOR - INTELLISENSE & SUGGESTIONS
  // ═══════════════════════════════════════════════════════════
  "editor.suggest.preview": true,
  "editor.suggestSelection": "first",
  "editor.acceptSuggestionOnCommitCharacter": false,
  "editor.tabCompletion": "on",
  "editor.quickSuggestions": {
    "other": true,
    "comments": false,
    "strings": false
  },
  "editor.inlineSuggest.enabled": true,
  "editor.parameterHints.enabled": false,

  // ═══════════════════════════════════════════════════════════
  // EDITOR - CODE FEATURES
  // ═══════════════════════════════════════════════════════════
  "editor.inlayHints.enabled": "offUnlessPressed",
  "editor.lightbulb.enabled": "off",
  "editor.codeLens": false,
  "editor.formatOnSave": false,

  // ═══════════════════════════════════════════════════════════
  // WORKBENCH - GENERAL
  // ═══════════════════════════════════════════════════════════
  "workbench.startupEditor": "none",
  "workbench.tree.indent": 14,
  "workbench.list.smoothScrolling": true,

  // ═══════════════════════════════════════════════════════════
  // WORKBENCH - EDITOR TABS
  // ═══════════════════════════════════════════════════════════
  "workbench.editor.showTabs": "multiple",
  "workbench.editor.tabSizing": "shrink",
  "workbench.editor.wrapTabs": false,
  "workbench.editor.pinnedTabsOnSeparateRow": true,
  "workbench.editor.labelFormat": "short",
  "workbench.editor.enablePreview": false,
  "workbench.editor.enablePreviewFromQuickOpen": true,
  "workbench.editor.enablePreviewFromCodeNavigation": true,
  "workbench.editor.closeOnFileDelete": true,

  // ═══════════════════════════════════════════════════════════
  // TERMINAL
  // ═══════════════════════════════════════════════════════════
  "terminal.integrated.fontFamily": "JetBrains Mono",
  "terminal.integrated.fontSize": 13,
  "terminal.integrated.lineHeight": 1.4,
  "terminal.integrated.cursorStyle": "line",
  "terminal.integrated.cursorBlinking": true,
  "terminal.integrated.smoothScrolling": true,
  "terminal.integrated.defaultProfile.linux": "bash",
  "terminal.integrated.defaultProfile.osx": "zsh",
  "terminal.integrated.defaultProfile.windows": "PowerShell",

  // ═══════════════════════════════════════════════════════════
  // EXPLORER
  // ═══════════════════════════════════════════════════════════
  "explorer.confirmDelete": false,
  "explorer.confirmPasteNative": false,
  "explorer.confirmDragAndDrop": false,
  "explorer.compactFolders": true,
  "explorer.sortOrder": "type",
  "explorer.autoReveal": true,

  // ═══════════════════════════════════════════════════════════
  // FILES
  // ═══════════════════════════════════════════════════════════
  "files.trimTrailingWhitespace": true,
  "files.insertFinalNewline": true,
  "files.exclude": {
    "**/.git": true,
    "**/.DS_Store": true
  },

  // ═══════════════════════════════════════════════════════════
  // BREADCRUMBS
  // ═══════════════════════════════════════════════════════════
  "breadcrumbs.enabled": false,
  "breadcrumbs.filePath": "off",
  "breadcrumbs.symbolPath": "off",

  // ═══════════════════════════════════════════════════════════
  // GIT & SOURCE CONTROL
  // ═══════════════════════════════════════════════════════════
  "git.autofetch": true,
  "git.enableSmartCommit": true,
  "scm.defaultViewMode": "tree",

  // ═══════════════════════════════════════════════════════════
  // SEARCH
  // ═══════════════════════════════════════════════════════════
  "search.exclude": {
    "**/node_modules": true,
    "**/dist": true,
    "**/build": true,
    "**/.git": true,
    "**/coverage": true
  },

  // ═══════════════════════════════════════════════════════════
  // PROBLEMS
  // ═══════════════════════════════════════════════════════════
  "problems.decorations.enabled": true,
  "problems.showCurrentInStatus": true,

  // ═══════════════════════════════════════════════════════════
  // WINDOW
  // ═══════════════════════════════════════════════════════════
  "window.title": "${activeEditorShort}${separator}${rootName}",
  "window.restoreWindows": "all",

  // ═══════════════════════════════════════════════════════════
  // ZEN MODE
  // ═══════════════════════════════════════════════════════════
  "zenMode.centerLayout": true,
  "zenMode.fullScreen": false,
  "zenMode.hideLineNumbers": false,
  "zenMode.restore": true,

  // ═══════════════════════════════════════════════════════════
  // SECURITY
  // ═══════════════════════════════════════════════════════════
  "security.workspace.trust.enabled": true,
  "security.workspace.trust.untrustedFiles": "open",
  "security.workspace.trust.startupPrompt": "never",

  // ═══════════════════════════════════════════════════════════
  // TYPESCRIPT
  // ═══════════════════════════════════════════════════════════
  "typescript.updateImportsOnFileMove.enabled": "always",
  "typescript.suggest.autoImports": true,

  // ═══════════════════════════════════════════════════════════
  // JAVASCRIPT
  // ═══════════════════════════════════════════════════════════
  "javascript.updateImportsOnFileMove.enabled": "always",
  "javascript.suggest.autoImports": true
}
```

---

## Icon Themes

Onyx Theme Color & Experience includes two companion icon themes for a complete visual experience:

**File Icons** — [Icons by Tal7aouy](https://marketplace.visualstudio.com/items?itemName=tal7aouy.icons)
Clean, minimal file icons that complement the dark aesthetic

**Product Icons** — [Feather Icons](https://marketplace.visualstudio.com/items?itemName=melishev.feather-vscode)
Consistent interface icons for buttons, menus, and toolbars

Both will be prompted for installation automatically.

---

## Language Support

Optimized syntax highlighting for:

JavaScript • TypeScript • React • Python • Java • C/C++ • C# • Go • Rust • HTML • CSS • SCSS • JSON • YAML • Markdown • Shell Scripts

---

## About

Onyx Theme Color & Experience is built for developers who value clarity and focus. The color palette is intentionally restrained to minimize distractions while maintaining excellent readability and visual hierarchy.

- **Version:** 1.1.2
- **License:** MIT

---

<p align="center">Enjoy coding with the refined experience</p>
