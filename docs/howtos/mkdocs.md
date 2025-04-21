---
date:
    created: 2025-04-21
tags:
    - mkdocs
---
# Material for MkDocs

## Links in neuen Tab öffnen

Damit Links in einem neuen Tab geöffnet werden und nicht im aktuellen Fenster müssen folgende Punkt beachtet werden.

1. Anpassung der mkdocs.yml Datei

    In der yml muss in den Markdown Extenstion die Erweiterung `attr_list` hinzugefügt werden.

    ```yml
    markdown_extensions:
    - attr_list
    ```

2. Die Links müssen um das HTML tag `{target="_blank"}` erweitert werden.

    ```txt
    [Name](URL){target="_blank"}
    ```

    ```txt
    [Github](https://github.com){target="_blank"}
    ```

    Ergebnis:

    [Github](https://github.com){target="_blank"}
