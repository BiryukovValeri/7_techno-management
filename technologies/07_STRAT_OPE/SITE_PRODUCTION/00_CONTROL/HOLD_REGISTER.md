# HOLD_REGISTER
| ID | Object | Type | Attempts | Impact | Blocking now? | Latest resolution point |
|---|---|---|---|---|---|---|
| H-001 | 10 Первоисточники books 01/02/06/07 DOCX (1.9–3.1 MB) | TECHNICAL | GitHub fetch_file base64 → empty content for >1MB; fetch_blob → UnicodeDecodeError on binary; GitHub fetch/raw → rejects non-UTF8 binary; standard reader therefore exhausted in current connector | Direct book-level provenance for individual STR/OPE/FIN/customer entries cannot be claimed READ | NO for S00 process recovery; YES for any downstream claim requiring direct book text | Before S02 PASS for affected public/evidence claims |
| H-002 | Individual 12 case files | COVERAGE | Indexed; catalog read | Detailed case claims not yet public-safe | NO S00 | S02/S08 before publishing individual cases |
| H-003 | Legacy 70 Site detailed content | INTENTIONAL DEFER | Indexed only after corpus recovery | Cannot govern truth; will be compared only after S01–S03 | NO | S03/S05 as legacy comparison |
