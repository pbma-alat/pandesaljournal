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

```

