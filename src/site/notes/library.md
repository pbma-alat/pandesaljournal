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
      - file.name
      - author
    cardSize: 160
    imageAspectRatio: 0.9
    image: note.image
    imageFit: contain

```

