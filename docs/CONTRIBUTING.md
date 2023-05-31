# Contribution Guidelines

**Read also in: [Español], [Português Brasileiro]**

Few are the possible contributions for this repository. Also note that it is good
to read the [Code of Conduct] and [Security Policy] firstly too.

Considering you've read all the above files, check below the ways you can contribute:

## Icons

As being the main resource of the repository, the icons have their specific traits
that must be observed before any contribution. These "rules", as they may be called
so, are the below ones:

- All icons must be **`SVG`** files;
- All icons must stay on the folder `icons`:
  - All file icons must stay on the subfolder `files`;
  - All folder icons must stay on the subfolder `folders`;
- All icons must follow the a naming rule:
  - All file icons must be named as `file_type_*.svg`;
  - All folder icons must be named as `folder_type_*.svg` and `folder_type_*_opened.svg`;
  - The wildcard **`*`** must be replaced with the name you want to be put on the
    `"icon"` JSON key, as the below example:

    ```json
    { "icon": "icon_name", "extensions": ["ext"], "format": "svg" }
    ```

Having all these requirement being understood, you can proceed.

### Requesting

Knowing the conventions of the icons, you can request one to be included on
this repository! Just submit the proper issue for it [here][request], filling the
form fields according with your requisition.

It is important to note that I can deny to do the icon, thus I still recommend to,
depending on your case, just fork my repo and have fun creating icons!

### Submitting

Currently all Pull Requests will be **rejected**. As soon as I understand the Pull
Requests Templates workflow, I will then accept them.

### Other Contributions

Contribution is always welcomed! So, if the icons were not your thing, there is
an issue for documentation revisions [here][revision], and, of course, giving a
star will be certainly very appreciated!

[Español]: CONTRIBUTING.ES.md
[Português Brasileiro]: CONTRIBUTING.PT-BR.md
[Code of Conduct]: CODE_OF_CONDUCT.md
[Security Policy]: SECURITY.md
[request]: https://github.com/Mestre-Tramador/Mestre-Tramador-VSCode-Icons/issues/new?assignees=Mestre-Tramador&labels=Type%3A+Feature+Request%2CStatus%3A+Opened&template=FEATURE-REQUEST.yml&title=%5BFEAT%5D%3A+
[revision]: https://github.com/Mestre-Tramador/Mestre-Tramador-VSCode-Icons/issues/new?assignees=Mestre-Tramador&labels=Type%3A+Docs+Revision%2CStatus%3A+Opened&template=DOCS-REVISION.yml&title=%5BDOCS%5D%3A+
