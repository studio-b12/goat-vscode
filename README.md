# goatfile

This is the Visual Studio Code extension adding language support for [Goatfiles](https://github.com/studio-b12/goat).

> **Warning**  
> This extension is currently not published on the VSCode marketplace. Therefore, see section [Manual Installation](#manual-installation) on how to install this extension.

## Features

### Syntax Highlighting

This extensions provides a very rudimentary syntax highlighting for `.goat` files.

![](https://github.com/studio-b12/goat-vscode/assets/16734205/720137ef-5230-421b-8496-8da6ef61b4b9)

<!-- ## Requirements

If you have any requirements or dependencies, add a section describing those and how to install and configure them. -->

<!-- ## Extension Settings

Include if your extension adds any VS Code settings through the `contributes.configuration` extension point.

For example:

This extension contributes the following settings:

* `myExtension.enable`: Enable/disable this extension.
* `myExtension.thing`: Set to `blah` to do something. -->

<!-- ## Known Issues

Calling out known issues can help limit users opening duplicate issues against your extension. -->

## Manual Installation

Because this extension is currently not listed on the VSCode Marketplace, you need to install the repository manually by cloning the contents of this repository into a `goatfile` directory in your `.vscode/extensions` directory.

```
git clone https://github.com/studio-b12/goat-vscode.git "$HOME/.vscode/extensions/goatfile"
```

If you are using VSCode Insiders, you need to use the following command.
```
git clone https://github.com/studio-b12/goat-vscode.git "$HOME/.vscode-insiders/extensions/goatfile"
```

If you are using Windows, you might want to use the following command.
```
git clone https://github.com/studio-b12/goat-vscode.git %USERPROFILE%\.vscode\extensions\goatfile
```

If this does not work, you can also download the extension package from the [latest build artifacts](https://github.com/studio-b12/goat-vscode/actions/workflows/artifacts.yaml). Simply download the `.vslx` and import it using the `Extensions: Install from VSIX...` command.

![](https://github.com/studio-b12/goat-vscode/assets/16734205/5e7a9fd7-35f0-4591-97cf-268c36849a39)

## Release Notes

Users appreciate release notes as you update your extension.

### 0.1.0

Initial pre-release of this extension.

---

© 2023 B12-Touch GmbH
https://b12-touch.de

Covered by the MIT License.