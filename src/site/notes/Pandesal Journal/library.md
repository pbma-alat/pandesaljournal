---
{"dg-publish":true,"permalink":"/pandesal-journal/library/","dg-note-properties":{}}
---



```base
filters:
  and:
    - file.inFolder("Bibliography")
views:
  - type: table
    name: View
    order:
      - file.name
      - file.tags
      - dg-publish
    columnSize:
      file.name: 365
      file.tags: 231
  - type: cards
    name: library
    filters:
      and:
        - file.inFolder("Bibliography")
    order:
      - author
      - title
    cardSize: 160
    imageAspectRatio: 0.95
    imageFit: contain
    image: note.image

```

