# VS Code Custom CSS Snippets

This repository aims to provide a shared list of CSS customizations of VS Code with the [vscode custom css extension](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css). This allows simpler sharing of custom themes and keeping multiple machines in sync.

## Usage

1. Install the [vscode custom css extension](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css)
2. Add links to css files to your settings

```json
"vscode_custom_css.imports": [
    "file:///local_css_files",
    "https://global_css_file"
],
```

3. Reload Custom css while connected to the Internet

## Examples

```json
"vscode_custom_css.imports": [
    "https://raw.githubusercontent.com/r-ggraham/vs-code-custom-css/main/VisualStudioCode.css"
],
```
![Current Personal Theme](./assets/screenshot_ascension.png)