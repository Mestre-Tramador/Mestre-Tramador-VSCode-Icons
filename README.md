<p id="mestre-tramador-vscode-icons" align="center">
  <a href="#mestre-tramador-vscode-icons">
    <img
      src="docs/assets/images/logo.png"
      alt="Mestre-Tramador VSCode Icons &quot;logo&quot;"
      width="547"
      height="250"
    />
  </a>
</p>

**Read it also in: [Español], [Português Brasileiro]**

---

<p id="badges" align="center">
  <a href="https://developer.mozilla.org/en-US/docs/Web/SVG">
    <img src="docs/assets/badges/svg.svg" alt="SVG" />
  </a>
</p>

This is my custom "extension" of the VS Code's extension [vscode-icons]. These SVG
icons are created based on my need for certain file types, specially with similar
names, as I find more easy to locate them by sight.

A full explanation on every icon can be found on the wiki, which you can access [here][wiki].

## Installation

If you already know about the customization of the extension, just drop all SVG
files you want on the `vsicons-custom-icons` folder and you are straight up to use
them. Otherwise, you may follow my simple tutorial right below:

<!-- #region Tutorial -->
<details>

<summary>
  Show...
</summary>

First check if you have VS Code [installed] or in a [portable] version, it may define
all the process:

### Installed VS Code

Just go to the below folder, as for your OS:

- **Windows:** `C:\Users\%USER%\AppData\Roaming\%CODE%\User\`
- **Linux:** `/home/$USER/.config/$CODE/User/`
- **Mac:** `/Users/$USER/Library/Application Support/$CODE/User/`

On the variables:

- **`%USER%`**/**`$USER`** refer to the username on the OS;
- **`%CODE%`**/**`$CODE`** refer to the VS Code folder name installed, which
  may vary as:
  - **Stable version:** `Code`;
  - **Insiders version:** `Code - Insiders`;
  - **3rd party distribution version:** `Code - OSS`;
  - **Development version:** `code-oss-dev`;

Then you just need to create a folder name `vsicons-custom-icons` and put all SVGs
you want.

### Portable VS Code

Just go to the below folder, as for your OS:

- **Windows:** `%VSCODE_HOME%\%DATA%\user-data\User\`
- **Linux:** `$VSCODE_HOME/$DATA/user-data/User/`
- **Mac:** `$VSCODE_HOME/$DATA/user-data/User/`

On the variables:

- **`%VSCODE_HOME%`**/**`$VSCODE_HOME`** refer to where VS Code is installed on
  your OS;
- **`%DATA%`**/**`$DATA`** refer to the VS Code's stored data folder, which
  may vary as:
  - **`Windows` and `Linux`, all versions:** `data`;
  - **`Mac`, stable version only:** `code-portable-data`;
  - **`Mac`, insiders version only:** `code-insiders-portable-data`;

Then you just need to create a folder name `vsicons-custom-icons` and put all SVGs
you want.

</details>
<!-- #endregion -->

For other infos, you can rely on the extension own's tutorial, right [here][vscode-icons-wiki].

My intention is on future versions create scripts to do this process easier.

## Contribution

My sincere suggestion is that you fork this repo and do it as best fit you. Otherwise,
contributions are welcomed, of course, and can be found on the Contribution Guidelines
[here][contribution].

## License

This repository, also the icons, is licensed under the Creative Commons Attribution
Share Alike 4.0 International License.

[Español]: docs/README.ES.md
[Português Brasileiro]: docs/README.PT-BR.md
[vscode-icons]: https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons
[wiki]: https://github.com/Mestre-Tramador/Mestre-Tramador-VSCode-Icons/wiki
[installed]: #installed-vs-code
[portable]: #portable-vs-code
[vscode-icons-wiki]: https://github.com/vscode-icons/vscode-icons/wiki/Custom
[contribution]: docs/CONTRIBUTING.md
