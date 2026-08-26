---
title: "Κλάση ImageRenderingOptions"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Κλάση Aspose.Svg.Rendering.Image.ImageRenderingOptions. Αναπαριστά τις επιλογές απόδοσης για το ImageDevice. Αυτές οι επιλογές χρησιμοποιούνται για τον καθορισμό της μορφής εξόδου της εικόνας, συμπίεσης, ανάλυσης κ.λπ."
type: docs
weight: 4940
url: /el/net/aspose.svg.rendering.image/imagerenderingoptions/
---
## ImageRenderingOptions class

Αναπαριστά τις επιλογές απόδοσης για το [`ImageDevice`](../imagedevice/). Αυτές οι επιλογές χρησιμοποιούνται για τον καθορισμό της μορφής εξόδου της εικόνας, της συμπίεσης, της ανάλυσης κ.λπ.

```csharp
public class ImageRenderingOptions : RenderingOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [ImageRenderingOptions](imagerenderingoptions/#constructor)() | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `ImageRenderingOptions`; Η μορφή PNG θα χρησιμοποιηθεί ως προεπιλεγμένη μορφή εικόνας. |
| [ImageRenderingOptions](imagerenderingoptions/#constructor_1)(*[ImageFormat](../imageformat/)*) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `ImageRenderingOptions` με την καθορισμένη μορφή εικόνας. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BackgroundColor](../../aspose.svg.rendering/renderingoptions/backgroundcolor/) { get; set; } | Λαμβάνει ή ορίζει το Color που θα γεμίζει το φόντο κάθε σελίδας. Η προεπιλεγμένη τιμή είναι Transparent. |
| [Compression](../../aspose.svg.rendering.image/imagerenderingoptions/compression/) { get; set; } | Ορίζει ή διαβάζει τη Συμπίεση (Compression) του Tagged Image File Format (TIFF) [`Compression`](../compression/). Από προεπιλογή, αυτή η ιδιότητα είναι LZW. |
| [Css](../../aspose.svg.rendering/renderingoptions/css/) { get; } | Λαμβάνει ένα αντικείμενο [`CssOptions`](../../aspose.svg.rendering/cssoptions/) που χρησιμοποιείται για τη διαμόρφωση της επεξεργασίας ιδιοτήτων css. |
| [Format](../../aspose.svg.rendering.image/imagerenderingoptions/format/) { get; set; } | Ορίζει ή διαβάζει το [`ImageFormat`](../imageformat/). Από προεπιλογή, αυτή η ιδιότητα είναι PNG. |
| override [HorizontalResolution](../../aspose.svg.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | Ορίζει ή λαμβάνει την οριζόντια ανάλυση για τις εικόνες εξόδου και εσωτερικές (που χρησιμοποιούνται κατά την επεξεργασία φίλτρων), σε pixel ανά ίντσα. Η προεπιλογή είναι 300 dpi. |
| [PageSetup](../../aspose.svg.rendering/renderingoptions/pagesetup/) { get; } | Λαμβάνει ένα αντικείμενο ρύθμισης σελίδας που χρησιμοποιείται για τη διαμόρφωση του εξόδου page-set. |
| [Text](../../aspose.svg.rendering.image/imagerenderingoptions/text/) { get; } | Λαμβάνει ένα αντικείμενο [`TextOptions`](../textoptions/) που χρησιμοποιείται για τη διαμόρφωση της απόδοσης κειμένου. |
| [UseAntialiasing](../../aspose.svg.rendering.image/imagerenderingoptions/useantialiasing/) { get; set; } | Καθορίζει εάν θα χρησιμοποιηθεί εξομάλυνση. Η προεπιλογή είναι η εξομάλυνση ενεργοποιημένη. |
| override [VerticalResolution](../../aspose.svg.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | Ορίζει ή λαμβάνει την κάθετη ανάλυση για τις εικόνες εξόδου και εσωτερικές (που χρησιμοποιούνται κατά την επεξεργασία φίλτρων), σε pixel ανά ίντσα. Η προεπιλογή είναι 300 dpi. |

### Δείτε επίσης

* class [RenderingOptions](../../aspose.svg.rendering/renderingoptions/)
* namespace [Aspose.Svg.Rendering.Image](../../aspose.svg.rendering.image/)
* assembly [Aspose.SVG](../../)
