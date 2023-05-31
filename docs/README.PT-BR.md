<p id="mestre-tramador-vscode-icons" align="center">
  <a href="#mestre-tramador-vscode-icons">
    <img
      src="assets/images/logo.png"
      alt="Mestre-Tramador VSCode Icons &quot;logo&quot;"
      width="547"
      height="250"
    />
  </a>
</p>

**Leia também em: [English], [Español]**

---

<p id="insignias" align="center">
  <a href="https://developer.mozilla.org/en-US/docs/Web/SVG">
    <img src="assets/badges/svg.svg" alt="SVG" />
  </a>
</p>

Esta é a minha "extensão" personalizada da extensão [vscode-icons] do VS Code.
Esses ícones SVG são criados com base na minha necessidade de determinados tipos
de arquivos, especialmente com nomes semelhantes, pois acho mais fácil localizá-los
de vista.

Uma explicação completa sobre cada ícone pode ser encontrada na wiki, que você pode
acessar [aqui][wiki].

## Instalação

Se você já conhece a personalização da extensão, basta soltar todos os arquivos
SVG que deseja na pasta `vsicons-custom-icons` e você estará pronto para usá-los.
Caso contrário, você pode seguir meu tutorial simples logo abaixo:

<!-- #region Tutorial -->
<details>

<summary>
  Mostrar...
</summary>

Primeiro verifique se você tem o VS Code [instalado] ou em uma versão [portátil],
isso pode definir todo o processo:

### VS Code Instalado

Basta ir para a pasta abaixo, tal qual o seu sistema operacional:

- **Windows:** `C:\Users\%USER%\AppData\Roaming\%CODE%\User\`
- **Linux:** `/home/$USER/.config/$CODE/User/`
- **Mac:** `/Users/$USER/Library/Application Support/$CODE/User/`

Sobre as variáveis:

- **`%USER%`**/**`$USER`** se refere ao nome de usuário no sistema operacional;
- **`%CODE%`**/**`$CODE`** se refere ao nome da pasta em que o VS Code foi instalado,
  que pode variar conforme:
  - **Versão "stable":** `Code`;
  - **Versão "insiders":** `Code - Insiders`;
  - **Versão de distribuição de terceiros:** `Code - OSS`;
  - **Versão "development":** `code-oss-dev`;

Então você só precisa criar uma pasta com o nome `vsicons-custom-icons` e colocar
todos os SVGs que desejar.

### VS Code Portátil

Basta ir para a pasta abaixo, tal qual o seu sistema operacional:

- **Windows:** `%VSCODE_HOME%\%DATA%\user-data\User\`
- **Linux:** `$VSCODE_HOME/$DATA/user-data/User/`
- **Mac:** `$VSCODE_HOME/$DATA/user-data/User/`

Sobre as variáveis:

- **`%VSCODE_HOME%`**/**`$VSCODE_HOME`** se refere a onde o VS Code está instalado
  no seu sistema operacional;
- **`%DATA%`**/**`$DATA`** se refere à pasta de dados armazenados do VS Code, que
  pode variar conforme:
  - **`Windows` e `Linux`, todas as versões:** `data`;
  - **`Mac`, versão "stable" apenas:** `code-portable-data`;
  - **`Mac`, versão "insiders" apenas:** `code-insiders-portable-data`;

Então você só precisa criar uma pasta com o nome `vsicons-custom-icons` e colocar
todos os SVGs que desejar.

</details>
<!-- #endregion -->

Para outras informações, você pode conferir no tutorial da própria extensão, [aqui][vscode-icons-wiki].

Minha intenção é em versões futuras criar scripts para facilitar esse processo.

## Contribuição

Minha sugestão sincera é que você faça uma fork deste repositório e trabalhe da
maneira que melhor lhe convier. Caso contrário, as contribuições são bem-vindas,
é claro, e podem ser encontradas nas Diretrizes de Contribuição [aqui][contribuição].

## Licença

Este repositório, assim como os ícones, está licenciado sob a licença Creative
Commons Attribution Share Alike 4.0 International.

[English]: ../README.md
[Español]: README.ES.md
[vscode-icons]: https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons
[wiki]: https://github.com/Mestre-Tramador/Mestre-Tramador-VSCode-Icons/wiki
[instalado]: #vs-code-instalado
[portátil]: #vs-code-portátil
[vscode-icons-wiki]: https://github.com/vscode-icons/vscode-icons/wiki/Custom
[contribuição]: CONTRIBUTING.PT-BR.md
