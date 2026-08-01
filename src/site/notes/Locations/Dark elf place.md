---
{"dg-publish":true,"permalink":"/locations/dark-elf-place/","noteIcon":"","dg-note-properties":{"type":["Location"],"aliases":null,"tags":null,"Age":null,"Status":"Active"}}
---

>[!info] Dark elf place
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

# Geography

# Structure

# History

# Inhabitants

```base
views:
  - type: table
    name: Table
    filters:
      and:
        - Origin.contains(link("Dark elf place"))
        - '!type.contains("Group")'
    order:
      - file.name
      - Profession
      - Status
      - Affiliation
    sort:
      - property: Status
        direction: ASC

```

# Culture 

# Areas of Interest

# Timeline
```aat-vertical

dateDisplayFormat: {year}
```
