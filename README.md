# diagrams

Playground for mermaid diagrams.

### References
* https://learning.oreilly.com/library/view/creating-software-with/9798888650219
* https://github.blog/2022-02-14-include-diagrams-markdown-files-mermaid/

```mermaid
sequenceDiagram
    participant dotcom
    participant iframe
    participant viewscreen
    dotcom->>iframe: loads html w/ iframe url
    iframe->>viewscreen: request template
    viewscreen->>iframe: html & javascript
    iframe->>dotcom: iframe ready
    dotcom->>iframe: set mermaid data on iframe
    iframe->>iframe: render mermaid
```
