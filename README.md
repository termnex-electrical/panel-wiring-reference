# Panel Wiring Reference Data

Open engineering reference tables for control-panel wiring components, maintained by **[Termnex](https://termnex.com/)**.

This repository provides machine-readable CSV and JSON datasets covering:

- **Wire ferrule collar colour codes (`0.5–50 mm²`)** across **DIN 46228-4**, **French (NF C 63-023)**, and **Special ("German")** sequences.
- **OEM-to-Termnex wire ferrule cross-reference (772 parts)** mapped by conductor cross-section, pin length, collar colour, and dimensional fit across 10 brands (Phoenix Contact, Weidmüller, Panduit, WAGO, TE Connectivity, Schneider Electric, American Electrical, Altech, CNC Tech, Conta-Clip).
- **Metric & PG nylon cable gland OD ranges** for quick panel-entry sizing.

## Datasets

| File | Format | Contents | Interactive Tool / Guide |
|---|---|---|---|
| [`data/wire-ferrule-colour-codes.csv`](data/wire-ferrule-colour-codes.csv) | CSV / [JSON](data/wire-ferrule-colour-codes.json) | 12 sizes (`0.5–50 mm²`) across DIN, French, and Special sequences | [Bootlace Ferrule Colour Codes Chart](https://termnex.com/blogs/bootlace-ferrule-colour-codes/) |
| [`data/wire-ferrule-oem-cross-reference.csv`](data/wire-ferrule-oem-cross-reference.csv) | CSV / [JSON](data/wire-ferrule-oem-cross-reference.json) | 772 OEM wire ferrule part numbers mapped to Termnex SKUs | [Interactive Wire Ferrule Cross-Reference](https://termnex.com/wire-ferrule-cross-reference/) |
| [`data/cable-gland-metric-pg-sizes.csv`](data/cable-gland-metric-pg-sizes.csv) | CSV / [JSON](data/cable-gland-metric-pg-sizes.json) | `M12–M63` and `PG7–PG48` cable OD clamping ranges | [Cable Gland Selector](https://termnex.com/cable-gland-selector/) |

## Quick Colour Code Reference (`0.5–50 mm²`)

| Cross-section | Approx. AWG | DIN 46228-4 | French (NF C 63-023) | Special ("German") |
|---|---|---|---|---|
| 0.5 mm² | 20 | White | White | Orange |
| 0.75 mm² | 18 | Grey | Blue | White |
| 1.0 mm² | 18 | Red | Red | Yellow |
| 1.5 mm² | 16 | Black | Black | Red |
| 2.5 mm² | 14 | Blue | Grey | Blue |
| 4.0 mm² | 12 | Grey | Orange | Grey |
| 6.0 mm² | 10 | Yellow | Green | Black |
| 10 mm² | 8 | Red | Brown | Ivory |
| 16 mm² | 6 | Blue | Ivory / White | Green |
| 25 mm² | 4 | Yellow | Black | Brown |
| 35 mm² | 2 | Red | Red | Beige |
| 50 mm² | 1 | Blue | Blue | Olive |

> **Note:** DIN 46228-4 colour assignments stop at `50 mm²`. Collar colour alone never uniquely identifies cross-section because colours repeat inside each system and shift across sequences.

## Free Online Tools & Printable PDFs

- **[Wire Ferrule Cross-Reference Finder](https://termnex.com/wire-ferrule-cross-reference/)** — Search single OEM part numbers or upload an Excel BOM.
- **[Wire Ferrule Size & Colour Chart](https://termnex.com/wire-ferrule-size-chart/)** — Full `0.14–150 mm²` dimensions and `mm² ↔ AWG` lookup.
- **[Cable Gland Selector](https://termnex.com/cable-gland-selector/)** — Filter Nylon, Brass, and Multi-Hole glands by cable OD, thread, and panel wall thickness.
- **[UL 486F vs CE & DIN 46228 Guide](https://termnex.com/blogs/wire-ferrule-ul-vs-ce/)** — Export panel compliance rules for EU and North American builds.
- **[Resource Center](https://termnex.com/resource-center/)** — Printable checklists, thread charts, and product catalogues (no registration required).

## License

Data and documentation in this repository are released under the [MIT License](LICENSE). Always verify final terminal compatibility, strip length, and project certification requirements against your governing panel standard.
