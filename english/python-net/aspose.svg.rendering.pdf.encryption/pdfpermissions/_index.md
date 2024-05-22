﻿---
title: PdfPermissions enumeration
second_title: Aspose.SVG for Python via .NET API References
description: 
type: docs
weight: 30
url: /python-net/aspose.svg.rendering.pdf.encryption/pdfpermissions/
is_root: false
---

## PdfPermissions enumeration

This enum represents user's permissions for a pdf.



The PdfPermissions type exposes the following members:

### Fields
| Field | Description |
| :- | :- |
| PRINT_DOCUMENT | (Security handlers of revision 2) Print the document. <br/>(Security handlers of revision 3 or greater) Print the document (possibly not at the highest quality level, depending on whether PrintingQuality is also set). |
| MODIFY_CONTENT | Modify the contents of the document by operations other than those controlled by ModifyTextAnnotations, FillForm, and 11. |
| EXTRACT_CONTENT | Security handlers of revision 2) Copy or otherwise extract text and graphics from the document,<br/>including extracting text and graphics (in support of accessibility to users with disabilities or for other purposes).<br/>(Security handlers of revision 3 or greater) Copy or otherwise extract text and graphics from the document by operations other than that controlled by<br/>ExtractContentWithDisabilities. |
| MODIFY_TEXT_ANNOTATIONS | Add or modify text annotations, fill in interactive form fields, and, if ModifyContent is also set, create or modify interactive form fields (including signature fields). |
| FILL_FORM | (Security handlers of revision 3 or greater) Fill in existing interactive form fields (including signature fields), even if ModifyTextAnnotations is clear. |
| EXTRACT_CONTENT_WITH_DISABILITIES | (Security handlers of revision 3 or greater) Extract text and graphics (in support of accessibility to users with disabilities or for other purposes). |
| ASSEMBLE_DOCUMENT | (Security handlers of revision 3 or greater) Assemble the document (insert, rotate, or delete pages and create bookmarks or thumbnail images), even if ModifyContent is clear. |
| PRINTING_QUALITY | (Security handlers of revision 3 or greater) Print the document to a representation from which a faithful digital copy of the PDF content could be generated.<br/>When this bit is clear (and bit 3 is set), printing is limited to a low-level representation of the appearance, possibly of degraded quality. |



### See Also
* module [`aspose.svg.rendering.pdf.encryption`](..)
