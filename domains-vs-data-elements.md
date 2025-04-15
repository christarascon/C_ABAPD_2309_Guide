## Difference: Domain vs Data Element

In ABAP Dictionary, Domains and Data Elements help define field attributes.

### Domain
- Defines **technical characteristics** of a field:
  - Data type
  - Length
  - Possible values (fixed values/ranges)
- Example: A domain for country code might be CHAR 3.

### Data Element
- Defines **semantic meaning** of a field:
  - Field label
  - Documentation
  - Domain link

### Summary

| Feature         | Domain                | Data Element            |
|----------------|------------------------|--------------------------|
| Technical Role | Data Type, Length     | Meaning & Label         |
| Reusability    | Used by many elements | Used by fields          |
| Example        | CHAR 10               | Customer Name           |
