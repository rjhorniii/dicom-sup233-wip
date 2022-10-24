# dicom-sup233-wip

This repository is for work in progress on DICOM Sup233.  It is not a substitute for the regular FTP.  It's a convenience for editor, co-authors, and other contributors to the WIP.  The FTP directory will continue to be used for official document reviews.

## Procedures for this repository

1. Git based delta can be used for puml, md, adoc, html, etc. documents that are line oriented text only files.  Versioned files is also permitted.
2. New files with new version numbers shall be used for ms word, xls, xml, and other similar documents that are not line oriented text only files.  Git based delta coding shall not be used.
3. Filenaming shall comply with the DICOM rules for any `supxxx.docx` or `cpxxx.docx` files.  This means filenames like `sup123_short-name_nnn.docx` where nnn increments by one for each new version.
4. For other non-text files, file naming shall be of the form basename-nnn.docx.  nnn shall start at 000 and increment by one for each new version.  E.g., `example-file-003.docx`
5. For puml (plantuml) files the puml shall be in the repository but the derived graphics files shall not.  Github can display puml diagrams in some circumstances, and after checkout to a local filesystem plantuml can be used to generate graphics files.  Exception, if a graphics file is separately edited so that it is not the same as the plantuml generated graphic, it can be added as a new file with version numbering.
 
