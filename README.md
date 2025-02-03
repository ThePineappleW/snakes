# Snakes

---

## VS Code language support for CS 4410

This extension adds support for syntax highlighting for the various homework languages.

- [x] Adder
- [ ] Boa
- [ ] Cobra

## Installation

I do not plan on putting this on the VS Code marketplace for obvious reasons.

To install:
1. Clone this repository.   
2. Open VS Code, and naviage to the `Extensions` menu.  
3. Select `...` > `Install from VSIX...`
4. Select the `.vsix` file in this repo.

## Development

I will try to keep this project updated throughout the semester. To make your own changes:

Install `vsce`:

```
npm install -g @vscode\vsce
```


Rebuild your `.vsix`:

```
vsce package
```

Then re-install the extension.
