# Source Corpus Import Audit

Audit date: 2026-09-27.

## Method

Each Mac folder was scanned once. Every file was hashed with SHA-256. Import used the original relative structure and excluded only proven operating-system or temporary metadata. A fresh destination manifest was then compared byte-for-byte with a clean source manifest.

No document was selected, rewritten, renamed, or discarded based only on its filename, date, or apparent version.

## Import matrix

| Technology | Source files | Imported content files | SHA parity | Exact duplicate groups inside source | Extra duplicate paths | Excluded junk |
|---|---:|---:|---:|---:|---:|---:|
| UM / DA | 110 | 106 | 106/106 | 0 | 0 | 4 |
| Assortment / Контур Маржи | 180 | 174 | 174/174 | 20 | 35 | 6 |
| Negotiations | 102 | 99 | 99/99 | 0 | 0 | 3 |
| Tribal Marketing | 126 | 124 | 124/124 | 0 | 0 | 2 |
| AI First | 106 | 104 | 104/104 | 2 | 2 | 2 |
| CLM | 121 | 118 | 118/118 | 0 | 0 | 3 |
| STRAT-OPE | 125 | 123 | 123/123 | 12 | 12 | 2 |
| **Total** | **870** | **848** | **848/848** | **34** | **49** | **22** |

Imported content size: **664,729,455 bytes**. No imported file exceeds GitHub's 100 MB single-file limit.

## Duplicate decision

The 49 extra byte-identical paths are not automatically removable duplicates:

- Assortment duplicates mostly connect canonical materials, self-contained Claude Design packages, Novamira transfer packages, and their copied visual assets.
- AI First contains identical spreadsheet templates under different product-stage directories.
- STRAT-OPE duplicates mostly connect canonical materials with a self-contained Claude Design launch package.

Removing one path can make a delivery package incomplete even when another identical blob exists elsewhere. Git stores identical content as one blob, so the repository is physically deduplicated while the required package paths remain intact.

Status: `PRESERVED / PATH ROLE REQUIRES REVIEW`.

## Version candidates

Mechanical filename grouping found three clear STRAT-OPE version families:

- `proSTRANSTVO_Операционная_Система_v0.2.docx` and `v1.0.docx`;
- `proSTRANSTVO_Справочник_Инструментов_И_Карточек_Знания_v0.2.xlsx` and `v1.0.xlsx`;
- `проSTRAнство*Клиентско*Смысловая*Модель*Сайта_V1_1.docx` and `V2.docx`.

The lower versions are archive candidates, not deletion-approved files. Canonicality must be confirmed from the technology's release registry and author decision before moving or deleting them.

## Safe cleanup candidates on Mac

Exactly 22 `.DS_Store` files were detected. They were excluded from Git and may be deleted after author confirmation. No content file has been deleted or moved on the Mac.

## Important UM correction

The canonical product documents exist and were imported with verified checksums:

- `technologies/01_UM_DA/30 Документация/Управленческая_Математика_УМ_Документация_08_Продуктовая_архитектура.docx`
- `technologies/01_UM_DA/30 Документация/Управленческая_Математика_УМ_Документация_09_Методика_проведения_продуктов.docx`

Any earlier claim that these files were absent from the accessible Mac corpus is false.
