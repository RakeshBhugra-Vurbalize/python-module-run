# python-module-run

A Visual Studio Code extension that allows you to effortlessly run Python modules directly from your workspace.

## Features

- **Run Python Modules with Ease**: Execute your Python modules using a simple command without leaving the editor.
- **Automatic Module Path Detection**: Automatically determines the Python module path based on the current file's location within your workspace.
- **Integrated Terminal Support**: Runs the Python command in the integrated terminal, allowing you to view output and interact as needed.

> **Tip:** You can bind the run command to a keyboard shortcut for quicker access.

## Requirements

- **Visual Studio Code**: Version 1.50.0 or higher.
- **Python**: Python must be installed and added to your system's PATH.

## Extension Settings

This extension does not add any additional settings. It works out of the box without requiring any configuration.

## Known Issues

- **Workspace Dependency**: The extension only works within a workspace that contains Python files (`.py`).
- **Standard Project Structure**: Assumes a standard Python package structure. Non-standard or deeply nested project structures might lead to incorrect module path detection.

## How to run on local
```
nvm use 22
npm install -g vsce
vsce package
```

Right click on 3 dots menu in extension and load the *.vsix file from this folder

## Release Notes

### 1.0.0

- Initial release of **python-module-run**.
- Added command to run Python modules based on the current file's path.
- Integrated terminal support for executing Python commands.

---

## Usage

1. **Open a Python File**: Navigate to any Python file within your workspace.
2. **Run the Module**:
   - Press `Ctrl+Shift+P` (Windows/Linux) or `Cmd+Shift+P` (macOS) to open the command palette.
   - Type `Run Python Module` and press `Enter`.
3. **View Output**: The integrated terminal will display the output of your Python module.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.

## License

**MIT

---

## Working with Markdown

You can author your README using Visual Studio Code. Here are some useful editor keyboard shortcuts:

- **Split the editor**: `Cmd+\` on macOS or `Ctrl+\` on Windows and Linux
- **Toggle preview**: `Shift+Cmd+V` on macOS or `Shift+Ctrl+V` on Windows and Linux
- **Trigger suggestion**: Press `Ctrl+Space` (Windows, Linux, macOS) to see a list of Markdown snippets

## For More Information

- [Visual Studio Code's Markdown Support](https://code.visualstudio.com/docs/languages/markdown)
- [Markdown Syntax Reference](https://www.markdownguide.org/basic-syntax/)

**Enjoy using python-module-run!**
