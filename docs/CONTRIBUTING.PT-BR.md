# Diretrizes de Contribuição

**Leia também em: [English], [Español]**

Poucas são as contribuições possíveis para este repositório. Observe também que
é bom ler primeiro o [Código de Conduta] e a [Política de Segurança].

Considerando que você leu todos os arquivos acima, confira abaixo as formas de contribuir:

## Ícones

Sendo o principal recurso do repositório, os ícones possuem suas especificidades
que devem ser observadas antes de qualquer contribuição. Essas "regras", como
podem ser chamadas, são as seguintes:

- Todos os ícones devem ser arquivos **`SVG`**;
- Todos os ícones devem ficar na pasta `icons`:
  - Todos os ícones de arquivos devem ficar na subpasta `files`;
  - Todos os ícones de pastas devem ficar na subpasta `folders`;
- Todos os ícones devem seguir uma regra de nomenclatura:
  - Todos os ícones de arquivos devem ser nomeados como `file_type_*.svg`;
  - Todos os ícones de pastas devem ser nomeados como `folder_type_*.svg` e `folder_type_*_opened.svg`;
  - O curinga **`*`** deve ser substituído pelo nome que você deseja colocar na
    chave `"icon"` do JSON, conforme exemplo abaixo:

    ```json
    { "icon": "icon_name", "extensions": ["ext"], "format": "svg" }
    ```

Com todos esses requisitos compreendidos, você pode prosseguir.

### Solicitando

Conhecendo as convenções dos ícones, você pode solicitar a inclusão de um neste
repositório! Basta enviar a issue adequada para isso [aqui][solicitação], preenchendo
os campos do formulário de acordo com a sua requisição.

É importante ressaltar que posso me negar a fazer o ícone, por isso ainda recomendo,
dependendo do seu caso, apenas fazer uma fork do meu repositório e se divertir
criando ícones!

### Enviando

Atualmente, todas as pull requests serão **rejeitadas**.
Assim que eu entender o fluxo de trabalho das templates de pull request, irei aceitá-las.

### Outras Contribuições

Contribuição é sempre bem-vinda! Então, se os ícones não são o seu forte, há uma
issue para revisões de documentação [aqui][revisão] e, claro, dar uma estrela
certamente será muito apreciado!

[English]: CONTRIBUTING.md
[Español]: CONTRIBUTING.ES.md
[Código de Conduta]: CODE_OF_CONDUCT.PT-BR.md
[Política de Segurança]: SECURITY.PT-BR.md
[solicitação]: https://github.com/Mestre-Tramador/Mestre-Tramador-VSCode-Icons/issues/new?assignees=Mestre-Tramador&labels=Type%3A+Feature+Request%2CStatus%3A+Opened&template=FEATURE-REQUEST.yml&title=%5BFEAT%5D%3A+
[revisão]: https://github.com/Mestre-Tramador/Mestre-Tramador-VSCode-Icons/issues/new?assignees=Mestre-Tramador&labels=Type%3A+Docs+Revision%2CStatus%3A+Opened&template=DOCS-REVISION.yml&title=%5BDOCS%5D%3A+
