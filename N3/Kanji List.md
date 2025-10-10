***
```base
properties:
  file.name:
    displayName: kanji
views:
  - type: table
    name: Table
    filters:
      and:
        - file.hasProperty("id")
    order:
      - file.name
      - class
      - reading
      - meaning
      - radical
      - grade
      - difficulty
      - status
      - id
    sort:
      - property: id
        direction: ASC
      - property: reading
        direction: ASC
      - property: difficulty
        direction: ASC
      - property: class
        direction: ASC
    columnSize:
      note.meaning: 172
      note.radical: 113
    rowHeight: tall

```

