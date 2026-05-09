---
{"dg-publish":true,"permalink":"/pandesal-journal/library/","dg-note-properties":{}}
---



```base
filters:
  and:
    - file.inFolder("Bibliography")
views:
  - type: list
    name: library
    filters:
      and:
        - file.inFolder("Bibliography")
    order:
      - author
      - title
      - file.name
    cardSize: 160
    imageAspectRatio: 0.95
    imageFit: contain
    image: note.image

```

