# Catalogue of a music library

*Catalogo di una biblioteca musicale*

**Microsoft Access** · 2018 · version 1.0  
Author: **Massimo Sbarbaro** ([ORCID 0009-0006-8965-9013](https://orcid.org/0009-0006-8965-9013))

## Overview

A compact catalogue of the scores and music books of a small music library. Each item records author, title, volume, opus, edition, reviser, section, instruments, condition, cataloguing data, archive location, year and notes, and is entered and searched through a single form.

I designed and programmed this application in 2018. It is published here in 2026 as part of the documented record of my software work, with a permanent DOI on Zenodo.

## Main functions

- Single data-entry and search form with a section list built from the existing values.

## Data

Single table `biblioteca`.

## Technology

Microsoft Access 2010+ format (.accdb).

## Repository contents

| Path | Content |
|---|---|
| `database/` | The Access application, emptied of all data. |
| `source/` | Plain-text export (UTF-8) of forms, reports, macros, VBA modules (`SaveAsText`) and of the SQL of every query. |
| `docs/schema.md` | Tables and fields. |

## What is not included

The database is published **empty**: every table has been emptied and the file compacted, so no record of the original data survives. Logos and names of the organisations that used the application have been removed from forms, reports and code, together with printer settings and any credential. Forms, reports, queries, macros and VBA code are otherwise unchanged and are also provided as plain text in `source/`.

## Related repositories

- [sheet-music-editions-inventory-access](https://github.com/massimosbarbaro/sheet-music-editions-inventory-access)
- [sound-music-archive-catalogue-access](https://github.com/massimosbarbaro/sound-music-archive-catalogue-access)

## How to cite

Use the citation metadata in [`CITATION.cff`](CITATION.cff) (GitHub: *Cite this repository*). Each release is archived on Zenodo with its own DOI.

> Sbarbaro, Massimo. *Catalogue of a music library (Microsoft Access, 2018)*. Software, version 1.0. GitHub: https://github.com/massimosbarbaro/music-library-catalogue-access

## License

Released under the [MIT License](LICENSE). © 2018 Massimo Sbarbaro.
