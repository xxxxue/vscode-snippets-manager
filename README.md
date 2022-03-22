# Snippets Manager

Create and edit snippets easily.

This extension is built over the default VS Code snippets system, wrapping it into a nice and intuitive UI, improving usability, and making snippets easy to create and edit. It supports user-custom snippets, global snippets and snippets from installed extensions.

## Features

### Manage snippets

Create, edit or delete snippets.

![feature create](images/manager.png)

### Create snippets

Select range to create a snippet.

<img src="images/create1.webp" width="500px">

### Edit snippets

Open `*.code-snippets` in Snippets Editor and edit it.

![feature edit](images/edit.webp)

You can right-click `*.code-snippets` file then left-click the `Open Whit...` option to select other editors to open `*.code-snippets` file or set the default editor to open `*.code-snippets` file.

### Undo/Redo

This extension provides a custom VS Code editor, so you can use VS Code shortcuts to undo/redo. By default, in Windows undo is `Ctrl+Z` redo is `Ctrl+Shift+Z`, in macOS undo is `⌘Z` redo is `⇧⌘Z`.

## Install via CLI

```bash
code --install-extension zjffun.snippetsmanager
```

## Release Notes

### [TODO]

### [Unreleased]

### v0.1.3

- Publish to Open VSX Registry.

### v0.1.2

- Added features delete snippet files.
- Added features delete confirm.

- Fix bug scroll to top when opening last few snippets.
- Fix bug refresh tree when create or delete snippets.

### v0.1.1

- Added features duplicate snippet.

### v0.1.0

- Added features update UI to webview-ui-toolkit.

- Improve documentation.

### v0.0.14

- Changed the GIF in document to WebP.

### v0.0.13

- Added features show error massage when an error occurred in the code snippets editor.
- Added features create snippets file.
- Added features show 'No snippets' when no snippets.

- Fix bug unparseable snippets disappear in trees.

### v0.0.12

- Added features set code snippets editor to default editor.

### v0.0.11

- Added features create snippet to specified file.
- Added features ask save to user snippets when can't find `activeWorkspaceFolder`.

### v0.0.10

- Fix bug when editor open with a malformed file.
- Fix bug editor state incorrect.
- Fix bug click edit snippet not work.

### v0.0.9

- Added features jump to selected snippet when click snippets.
- Added features edit selected snippet when click edit snippet.
- Added features support explorer file open editor.

- Fix bug when parse snippets file error.

### v0.0.8

- Fix bug when have no `.vscode` folder.

### v0.0.6

- Added features show all `*.code-snippets` in explorer.
- Added features toggle source and editor.

- Fix bug when open empty snippets file.

### v0.0.5

- Added features add snippets in editor.

### v0.0.4

- Added features `*.code-snippets` file editor.

### v0.0.3

- Changed icon and keywords.

### v0.0.2

- Changed icon.

### v0.0.1

- Added features create, edit and delete snippets.

## Contribute

To contribute to this VSCode extension. Open the root folder of this repo, then run

1. `yarn install`
2. `yarn compile`
3. Use VSCode debugging function (in menu `run`-`Start Debugging[F5]`)
