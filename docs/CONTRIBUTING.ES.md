# Pautas de Contribución

**Lea también en: [English], [Português Brasileiro]**

Pocas son las posibles contribuciones para este repositorio. También tenga en
cuenta que es bueno leer el [Código de Conducta] y la [Política de Seguridad] en
primer lugar.

Teniendo en cuenta que ha leído todos los archivos anteriores, consulte abajo las
formas en que puede contribuir:

## Íconos

Al ser el principal recurso del repositorio, los íconos tienen sus particularidades
que deben ser observadas antes de cualquier aporte. Estas "reglas", como pueden
llamarse así, son las siguientes:

- Todos los íconos deben ser archivos **`SVG`**;
- Todos los iconos deben permanecer en la carpeta `icons`:
  - Todos los iconos de archivos deben permanecer en la subcarpeta `files`;
  - Todos los iconos de carpetas deben permanecer en la subcarpeta `folders`;
- Todos los íconos deben seguir una regla de nomenclatura:
  - Todos los íconos de archivos deben tener el nombre `file_type_*.svg`;
  - Todos los íconos de carpetas deben tener el nombre `folder_type_*.svg` y `folder_type_*_opened.svg`;
  - El comodín **`*`** debe ser reemplazado con el nombre que desea poner en la
    clave `"icon"` del JSON, como el siguiente ejemplo:

    ```json
    { "icon": "icon_name", "extensions": ["ext"], "format": "svg" }
    ```

Habiendo entendido todos estos requisitos, puede continuar.

### Solicitando

Conociendo las convenciones de los íconos, ¡puede solicitar que se incluya uno en
este repositorio! Simplemente envíe la issue correspondiente [aquí][solicitud],
completando los campos del formulario de acuerdo con su solicitud.

Es importante tener en cuenta que puedo negarme a hacer el ícono, por lo que aún
recomiendo, dependiendo de su caso, simplemente haga un fork de mi repositorio y
diviertese creando íconos.

### Sometiendo

Actualmente, todas las pull requests serán **rechazadas**. Tan pronto como
comprenda el flujo de trabajo de las plantillas de pull request, las aceptaré.

### Otras Contribuciones

¡Contribución siempre es bienvenida! Entonces, si los íconos no són tu estilo,
hay una issue para las revisiones de la documentación [aquí][revisión] y, por
supuesto, ¡dar una estrella será sin duda muy apreciado!

[English]: CONTRIBUTING.md
[Português Brasileiro]: CONTRIBUTING.PT-BR.md
[Código de Conducta]: CODE_OF_CONDUCT.ES.md
[Política de Seguridad]: SECURITY.ES.md
[solicitud]: https://github.com/Mestre-Tramador/Mestre-Tramador-VSCode-Icons/issues/new?assignees=Mestre-Tramador&labels=Type%3A+Feature+Request%2CStatus%3A+Opened&template=FEATURE-REQUEST.yml&title=%5BFEAT%5D%3A+
[revisión]: https://github.com/Mestre-Tramador/Mestre-Tramador-VSCode-Icons/issues/new?assignees=Mestre-Tramador&labels=Type%3A+Docs+Revision%2CStatus%3A+Opened&template=DOCS-REVISION.yml&title=%5BDOCS%5D%3A+
