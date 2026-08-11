---
{"dg-publish":true,"permalink":"/1-hero-s-party/hero-s-party/","noteIcon":"","dg-note-properties":{"type":["Group"],"aliases":null,"tags":null,"Status":"Active"}}
---

# Members

```base
properties:
  file.name:
    displayName: Name
views:
  - type: table
    name: Table
    filters:
      and:
        - Affiliation.contains(link("Hero's Party"))
    order:
      - file.name
      - aliases
      - Profession
      - Status
    sort:
      - property: image
        direction: ASC
  - type: cards
    name: Party Members
    filters:
      and:
        - Affiliation.contains(link("Hero's Party"))
    image: note.image

```

  