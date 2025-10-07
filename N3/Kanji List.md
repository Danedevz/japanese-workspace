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
        - file.inFolder("japanese-workspace/N3/Kanji")
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
      note.radical: 113

```

