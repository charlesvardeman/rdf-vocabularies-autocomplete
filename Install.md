# Instructions to build extension locally

Full instructions on packaging extensions can be found in the VSCode [extension docs](https://code.visualstudio.com/api/working-with-extensions/publishing-extension).

1. Install the vscode extension engine globally `npm install -g vsce`.

2. Install node dependencies. `npm install`

3. Run `vsce package` to build VSIX extension package.
4. Install extension `code --install-extension my-extension-0.0.1.vsix`.
