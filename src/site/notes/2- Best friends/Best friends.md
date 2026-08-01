---
{"dg-publish":true,"permalink":"/2-best-friends/best-friends/","noteIcon":"","dg-note-properties":{"type":["Group"],"aliases":null,"tags":null,"Age":null,"Origin":null,"Affiliation":null,"Status":"Active"}}
---

>[!info] Best friends
>![[]]
>**Origin** `= this.origin`
>
> **Aliases**  
> `= this.aliases`
>
> **Affiliations**
> `= this.affiliation`
> 
> **Languages**
> `= this.language`
> 
> **Status**: Active


```base
properties:
  file.name:
    displayName: Name
views:
  - type: table
    name: Table
    filters:
      and:
        - Affiliation.contains(link("Best friends"))
    order:
      - file.name
      - aliases
      - Profession
      - Affiliation
      - Status
    sort:
      - property: Status
        direction: ASC
      - property: file.name
        direction: DESC
  - type: cards
    name: Party Members
    filters:
      and:
        - Affiliation.contains(link("Best friends"))
    image: note.image
  - type: list
    name: Party List
    filters:
      and:
        - Affiliation.contains(link("Best friends"))
    indentProperties: false

```
