# Extrastrap
Extrastrap is a small library of Bootstrap-like utility classes made to extend your Bootstrap usage that I find I need to use the most. If I end up finding myself needing to write more utilities often, I'll add them to this.
### Utilities:
- Cursors
- Sizing
- Z-Indexes
### Usage
- Cursors:
  - [All cursors](https://developer.mozilla.org/en-US/docs/Web/CSS/cursor) from the **CSS User Interface 4** spec are included
  - Cursor classes are named as `cursor-type`, for example `cursor-pointer`
- Sizing:
  - Extrastrap adds intervals of 5 rather than the Bootstrap 25 for all sizing utilities, allowing sizes 5-100 rather than 25-100
  - Extrastrap also adds extra sizing classes:
    - Minimum percentage-based width with `mi-w-interval`, for example `mi-w-85`
    - Maximum viwport-based width with `max-vw-interval`, for example `max-vw-85`
    - Minimum rem-based width with `min-rw-interval`, for example `min-rw-85`
    - Rem-based width with `rw-interval`, for example `rw-85`
    - Maximum rem-based width with `max-vw-interval`, for example `max-rw-85`
    - Minimum percentage-based height with `mi-h-interval`, for example `mi-h-85`
    - Maximum viwport-based height with `max-vh-interval`, for example `max-vh-85`
    - Minimum rem-based height with `min-rh-interval`, for example `min-rh-85`
    - Rem-based height with `rh-interval`, for example `rh-85`
    - Maximum rem-based height with `max-vh-interval`, for example `max-rh-85`
- Z-Indexes:
  - 7000 with `z1`
  - 6000 with `z2`
  - 5000 with `z3`
  - 4000 with `z4`
  - 3000 with `z5`
  - 2000 with `z6`
  - Auto with `zauto`