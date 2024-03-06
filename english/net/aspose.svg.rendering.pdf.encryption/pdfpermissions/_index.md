---
title: PdfPermissions Enum
second_title: Aspose.SVG for .NET API Reference
description: Aspose.Svg.Rendering.Pdf.Encryption.PdfPermissions enum. This enum represents users permissions for a pdf
type: docs
weight: 4660
url: /net/aspose.svg.rendering.pdf.encryption/pdfpermissions/
---
## PdfPermissions enumeration

This enum represents user's permissions for a pdf.

```csharp
[Flags]
public enum PdfPermissions
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| PrintDocument | `4` | (Security handlers of revision 2) Print the document. (Security handlers of revision 3 or greater) Print the document (possibly not at the highest quality level, depending on whether PrintingQuality is also set). |
| ModifyContent | `8` | Modify the contents of the document by operations other than those controlled by ModifyTextAnnotations, FillForm, and 11. |
| ExtractContent | `10` | Security handlers of revision 2) Copy or otherwise extract text and graphics from the document, including extracting text and graphics (in support of accessibility to users with disabilities or for other purposes). (Security handlers of revision 3 or greater) Copy or otherwise extract text and graphics from the document by operations other than that controlled by ExtractContentWithDisabilities. |
| ModifyTextAnnotations | `20` | Add or modify text annotations, fill in interactive form fields, and, if ModifyContent is also set, create or modify interactive form fields (including signature fields). |
| FillForm | `100` | (Security handlers of revision 3 or greater) Fill in existing interactive form fields (including signature fields), even if ModifyTextAnnotations is clear. |
| ExtractContentWithDisabilities | `200` | (Security handlers of revision 3 or greater) Extract text and graphics (in support of accessibility to users with disabilities or for other purposes). |
| AssembleDocument | `400` | (Security handlers of revision 3 or greater) Assemble the document (insert, rotate, or delete pages and create bookmarks or thumbnail images), even if ModifyContent is clear. |
| PrintingQuality | `800` | (Security handlers of revision 3 or greater) Print the document to a representation from which a faithful digital copy of the PDF content could be generated. When this bit is clear (and bit 3 is set), printing is limited to a low-level representation of the appearance, possibly of degraded quality. |

### See Also

* namespace [Aspose.Svg.Rendering.Pdf.Encryption](../../aspose.svg.rendering.pdf.encryption/)
* assembly [Aspose.SVG](../../)
