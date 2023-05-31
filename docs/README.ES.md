<p id="mestre-tramador-vscode-icons" align="center">
  <a href="#mestre-tramador-vscode-icons">
    <img
      src="assets/images/logo.png"
      alt="Mestre-Tramador VSCode Icons &quot;logotipo&quot;"
      width="547"
      height="250"
    />
  </a>
</p>

**Léelo también en: [English], [Português Brasileiro]**

---

<p id="insignias" align="center">
  <a href="https://developer.mozilla.org/en-US/docs/Web/SVG">
    <img src="assets/badges/svg.svg" alt="SVG" />
  </a>
</p>

Esta es mi "extensión" personalizada de la extensión [vscode-icons] de VS Code.
Estos íconos SVG se crean en base a mi necesidad de ciertos tipos de archivos,
especialmente con nombres similares, ya que me resulta más fácil ubicarlos a simple
vista.

Puede encontrar una explicación completa de cada icono en la wiki, a la que puede
acceder [aquí][wiki].

## Instalación

Si ya conoce la personalización de la extensión, simplemente suelte todos los
archivos SVG que desee en la carpeta `vsicons-custom-icons` y podrá usarlos
directamente. De lo contrario, puede seguir mi sencillo tutorial abajo:

<!-- #region Tutorial -->
<details>

<summary>
  Mostrar...
</summary>

Primero verifique si tiene VS Code [instalado] o en una versión [portátil], eso
define a todo el proceso:

### VS Code Instalado

Simplemente vaya a la carpeta abajo, tal cual a su sistema operativo:

- **Windows:** `C:\Users\%USER%\AppData\Roaming\%CODE%\User\`
- **Linux:** `/home/$USER/.config/$CODE/User/`
- **Mac:** `/Users/$USER/Library/Application Support/$CODE/User/`

Sobre las variables:

- **`%USER%`**/**`$USER`** se refiere al nombre de usuario en el sistema operativo;
- **`%CODE%`**/**`$CODE`** se refiere al nombre de la carpeta en que VS Code fué
  instalado, que puede variar de acuerdo con:
  - **Versión "stable":** `Code`;
  - **Versión "insiders":** `Code - Insiders`;
  - **Versión de distribución de terceros:** `Code - OSS`;
  - **Versión "development":** `code-oss-dev`;

Luego, solo necesita crear una carpeta con el nombre `vsicons-custom-icons` y
colocar todos los SVG que desee.

### VS Code Portátil

Simplemente vaya a la carpeta abajo, tal cual a su sistema operativo:

- **Windows:** `%VSCODE_HOME%\%DATA%\user-data\User\`
- **Linux:** `$VSCODE_HOME/$DATA/user-data/User/`
- **Mac:** `$VSCODE_HOME/$DATA/user-data/User/`

Sobre las variables:

- **`%VSCODE_HOME%`**/**`$VSCODE_HOME`** se refiere a dónde está instalado VS Code
  en su sistema operativo;
- **`%DATA%`**/**`$DATA`** se refiere a la carpeta de datos almacenados de VS Code,
  que puede variar de acuerdo con:
  - **`Windows` y `Linux`, todas las versiones:** `data`;
  - **`Mac`, versión "stable" solamente:** `code-portable-data`;
  - **`Mac`, versión "insiders" solamente:** `code-insiders-portable-data`;

Luego, solo necesita crear una carpeta con el nombre `vsicons-custom-icons` y
colocar todos los SVG que desee.

</details>
<!-- #endregion -->

Para otras informaciones, puede verificar el tutorial de la extensión, justo [aquí][vscode-icons-wiki].

Mi intención es que en futuras versiones se creen scripts para hacer este proceso
más fácil.

## Contribución

Mi sugerencia sincera es que haga un fork de este repositorio y trabaje como
mejor te convenga. De lo contrario, las contribuciones son bienvenidas, por
supuesto, y se pueden encontrar en las Pautas de Contribución [aquí][contribución].

## Licencia

Este repositorio, al igual que los íconos, tiene la licencia Creative Commons
Attribution Share Alike 4.0 International.

[English]: ../README.md
[Português Brasileiro]: README.PT-BR.md
[vscode-icons]: https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons
[wiki]: https://github.com/Mestre-Tramador/Mestre-Tramador-VSCode-Icons/wiki
[instalado]: #vs-code-instalado
[portátil]: #vs-code-portátil
[vscode-icons-wiki]: https://github.com/vscode-icons/vscode-icons/wiki/Custom
[contribución]: CONTRIBUTING.ES.md
