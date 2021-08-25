# Extrastrap
Extrastrap is a small library of Bootstrap-like utility classes made to extend your Bootstrap usage.
### Utilities:
- Cursors
- Z-Indexes
### Usage
- Cursors:
  - [All cursors](https://developer.mozilla.org/en-US/docs/Web/CSS/cursor) from the **CSS User Interface 4** spec are included
  - Cursor classes are named as `cursor-type`, for example `cursor-pointer`
- Z-Indexes:
  - Z-Indexes go from 2000 to 7000, high enough to overlay on top of Bootstrap styles but low enough to fall below styles like `z-index: 999999;`
  - Z-Indexes are named the same way as Bootstrap font size classes are named
    - 7000 with `z1`
    - 6000 with `z2`
    - 5000 with `z3`
    - 4000 with `z4`
    - 3000 with `z5`
    - 2000 with `z6`
    - Auto with `zauto`
### Contributing
If you want to suggest an addition to Extrastrap or want to add something yourself, either open an issue or PR respectively.