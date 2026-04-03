---
{"dg-publish":true,"permalink":"/library/","dg-note-properties":{}}
---



```base
filters:
  and:
    - file.inFolder("Bibliography")
views:
  - type: cards
    name: library
    filters:
      and:
        - file.inFolder("Bibliography")
    order:
      - title
      - author
    cardSize: 160
    imageAspectRatio: 0.95
    imageFit: contain
    image: note.image
  - type: table
    name: list
    order:
      - dg-publish
      - file.name
      - author
      - title
      - image
    sort:
      - property: file.name
        direction: ASC
    markers: number
    indentProperties: false
    columnSize:
      note.dg-publish: 42
      note.author: 145
      note.title: 196
      note.image: 191

```

