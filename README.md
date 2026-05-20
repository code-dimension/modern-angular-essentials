# Modern Angular Essentials Pack 🚀

[![Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/codedimension.cd-modern-angular-essentials.svg?style=for-the-badge&color=e03e2f)](https://marketplace.visualstudio.com/items?itemName=codedimension.cd-modern-angular-essentials)
[![Installs](https://img.shields.io/visual-studio-marketplace/i/codedimension.cd-modern-angular-essentials.svg?style=for-the-badge&color=0f172a)](https://marketplace.visualstudio.com/items?itemName=codedimension.cd-modern-angular-essentials)
[![Open VSX](https://img.shields.io/open-vsx/v/codedimension/cd-modern-angular-essentials?style=for-the-badge&color=4c1d95)](https://open-vsx.org/extension/codedimension/cd-modern-angular-essentials)
[![License](https://img.shields.io/github/license/code-dimension/modern-angular-essentials?style=for-the-badge&color=22c55e)](LICENSE)

**Modern Angular Essentials** is the ultimate, curated extension pack designed by **Code Dimension** to deliver a premium, high-productivity environment for TypeScript, Angular, and full-stack front-end developers. Whether you're working on advanced reactive patterns, designing with Tailwind CSS, or looking for beautiful, clean developer tooling, this pack contains everything you need to build at speed.

---

## What's Included? 📦

This pack bundles **13 essential extensions** to elevate your VS Code workflow:

| Extension Name | Extension ID | Rationale & Key Features |
| :--- | :--- | :--- |
| **Angular Language Service** | `Angular.ng-template` | Provides core editor capabilities, autocompletion, error checking, and navigation inside Angular templates (HTML and inline). |
| **ESLint** | `dbaeumer.vscode-eslint` | Integrates ESLint into VS Code to enforce clean code rules and catch JavaScript/TypeScript issues in real time. |
| **Prettier - Code Formatter** | `esbenp.prettier-vscode` | Standardizes format-on-save across HTML, TypeScript, SCSS/CSS, and JSON for seamless code styling. |
| **Tailwind CSS IntelliSense** | `bradlc.vscode-tailwindcss` | Offers intelligent autocomplete, CSS previews, and style linting for rapid utility-first CSS styling. |
| **Pretty TypeScript Errors** | `yoavbls.pretty-ts-errors` | Transforms convoluted and hard-to-read TypeScript compiler errors into human-friendly, readable visual blocks. |
| **GitLens — Git supercharged** | `eamodio.gitlens` | Unlocks powerful Git authorship insight, visual file history, and inline blame to seamlessly track your code evolution. |
| **Spek** | `kewang.spek-vscode` | Provides Kotlin Spek framework support, making testing and spec execution easy within your editor. |
| **Copilot Theme** | `BenjaminBenais.copilot-theme` | A beautiful, high-contrast, premium dark theme inspired by the modern look of GitHub Copilot. |
| **Todo+** | `fabiospamponato.vscode-todo-plus` | Manages todo lists with support for projects, tags, timers, and customized task-tracking formats. |
| **Auto Close Tag** | `formulahendry.auto-close-tag` | Automatically adds HTML/XML close tags, speeding up template design and nesting. |
| **Auto Rename Tag** | `formulahendry.auto-rename-tag` | Automatically renames paired HTML/XML tags in real time to avoid syntax errors. |
| **EditorConfig for VS Code** | `EditorConfig.EditorConfig` | Enforces consistent coding styles and formatting settings across teams and IDEs. |
| **Figure** | `imfeniljikadara.figure` | Integrates simple, elegant ASCII / drawing support directly in your editor workspace. |

---

## Extension Spotlights 💡

### 🔺 Modern Angular & UI Styling
- **Angular Language Service**: Seamlessly integrates with Angular templates. Jump directly from templates to component TypeScript definitions using `Ctrl+Click`/`Cmd+Click`.
- **Tailwind CSS**: Instant autocompletion of CSS classes. Hover over any class name to see the underlying CSS values.

### 🎨 Beautiful & Intuitive Workspace
- **Copilot Theme**: Designed to minimize eye strain and offer beautiful visual separation of code syntax.
- **Pretty TS Errors**: No more scrolling through 20 lines of nested object type errors. Read exactly what is wrong immediately!

### ⚡ Professional Quality Assurance
- **ESLint & Prettier**: The industry standard for automated format-on-save and style linting.
- **GitLens**: Understand file history instantly without breaking your flow.

---

## How to Install 🚀

### Option 1: VS Code UI
1. Open VS Code.
2. Go to the **Extensions** view (`Ctrl+Shift+X` or `Cmd+Shift+X`).
3. Search for `codedimension.cd-modern-angular-essentials`.
4. Click **Install**.

### Option 2: Command Line
```bash
code --install-extension codedimension.cd-modern-angular-essentials
```

### Option 3: Install from Local `.vsix`
If you are using the pre-compiled local `.vsix` file:
1. Open the Extensions side-bar.
2. Click the `...` menu (top right of the Extensions panel).
3. Select **Install from VSIX...** and choose the `modern-angular-essentials-1.0.1.vsix` file.

---

## Publishing and Packaging (For Maintainers) 🛠️

If you need to rebuild or publish this extension pack to marketplaces:

### Requirements
Ensure you have Node.js and npm installed.

### Build and Package (Local VSIX)
To package the extension into a shareable `.vsix` bundle locally:
```bash
# Package the extension without installing extra dependencies
npx @vscode/vsce package --no-dependencies
```

### Publish to VS Code Marketplace
1. Make sure you have a publisher account for `codedimension` on the [Marketplace Console](https://marketplace.visualstudio.com/manage).
2. Log in using your Personal Access Token (PAT):
   ```bash
   npx @vscode/vsce login codedimension
   ```
3. Publish:
   ```bash
   npx @vscode/vsce publish
   ```

### Publish to Open VSX Registry (vsox)
1. Register your publisher `codedimension` on [Open VSX](https://open-vsx.org/).
2. Log in using your Open VSX token:
   ```bash
   npx ovsx login codedimension
   ```
3. Publish:
   ```bash
   npx ovsx publish modern-angular-essentials-1.0.1.vsix
   ```

---

## License 📄

This extension pack is open-source and licensed under the [MIT License](LICENSE).

---

<p align="center">Made with ❤️ by <b>Code Dimension</b></p>
