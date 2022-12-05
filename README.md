<p align="center" style="text-align: center;">
<img src="jevkodata.png" width="80" height="80" /><br/>
<a href="https://jevko.org">jevko.org</a><br/>
<span>[EXPERIMENTAL]</span>
</p>

# jevkodata-basic-highlighting-vscode

Basic syntax highlighting for .jevkodata in Visual Studio Code.

This extension is published to the [Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=jevko.jevkodata-basic-highlighting) as well as the [Open VSX Registry](https://open-vsx.org/extension/jevko/jevkodata-basic-highlighting).

## Installation

Launch VS Code Quick Open (Ctrl+P), paste the following command, and press enter.

```
ext install jevko.jevkodata-basic-highlighting
```

## Jevko CLI

To make this extension useful, it is recommended to install [Jevko CLI](https://github.com/jevko/jevko-cli) -- a command line program which can convert between Jevko formats and HTML/XML/JSON.

## Related extensions

* [jevkoml-basic-highlighting](https://github.com/jevko/jevkoml-basic-highlighting-vscode): [Open VSX Registry](https://open-vsx.org/extension/jevko/jevkoml-basic-highlighting) | [Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=jevko.jevkoml-basic-highlighting)

## Features

Basic syntax highlighting for .jevkodata that works in Visual Studio Code.

![screenshot 1](screenshot1.png)
![screenshot 2](screenshot2.png)
![screenshot 3](screenshot3.png)

<!-- Includes experimental support for heredocs. -->

<!-- todo: expand on heredocs -->

<!-- ## Requirements

If you have any requirements or dependencies, add a section describing those and how to install and configure them. -->

<!-- ## Extension Settings

Include if your extension adds any VS Code settings through the `contributes.configuration` extension point.

For example:

This extension contributes the following settings:

* `myExtension.enable`: enable/disable this extension
* `myExtension.thing`: set to `blah` to do something -->

## Release Notes

See [CHANGELOG.md](CHANGELOG.md).

## Installation of the latest development snapshot directly from the git repository

To start using this extension with Visual Studio Code copy the folder that contains this repository into the `<user home>/.vscode/extensions` folder and restart Code.

Files with the .jevkodata extension now should have syntax highlighting.