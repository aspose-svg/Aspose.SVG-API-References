---
title: "ImageDevice.ImageGraphicContext Κλάση"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Aspose.Svg.Rendering.Image.ImageDeviceImageGraphicContext class. Διατηρεί τις τρέχουσες παραμέτρους ελέγχου γραφικών για το ImageDevice. Αυτές οι παράμετροι ορίζουν το παγκόσμιο πλαίσιο μέσα στο οποίο εκτελούνται οι λειτουργίες γραφικών."
type: docs
weight: 4920
url: /el/net/aspose.svg.rendering.image/imagedevice.imagegraphiccontext/
---
## ImageDevice.ImageGraphicContext class

Κρατά τις τρέχουσες παραμέτρους ελέγχου γραφικών για το [`ImageDevice`](../imagedevice/). Αυτές οι παράμετροι ορίζουν το παγκόσμιο πλαίσιο μέσα στο οποίο εκτελούνται οι τελεστές γραφικών.

```csharp
public class ImageGraphicContext : GraphicContext
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [ImageGraphicContext](../../aspose.svg.rendering.image/imagedevice.imagegraphiccontext/.ctor)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| virtual [CharacterSpacing](../../aspose.svg.rendering/graphiccontext/characterspacing/) { get; set; } | Ορίζει ή λαμβάνει το διάστημα χαρακτήρων. |
| [CurrentElement](../../aspose.svg.rendering/graphiccontext/currentelement/) { get; } | Λαμβάνει το τρέχον επεξεργασμένο στοιχείο. |
| virtual [FillBrush](../../aspose.svg.rendering/graphiccontext/fillbrush/) { get; set; } | Ορίζει ή λαμβάνει το αντικείμενο πινέλου που χρησιμοποιείται για τη γέμιση των εσωτερικών περιοχών των διαδρομών. |
| virtual [Font](../../aspose.svg.rendering/graphiccontext/font/) { get; set; } | Ορίζει ή λαμβάνει το αντικείμενο γραμματοσειράς TrueType που χρησιμοποιείται για την απόδοση κειμένου. |
| virtual [FontSize](../../aspose.svg.rendering/graphiccontext/fontsize/) { get; set; } | Ορίζει ή λαμβάνει το μέγεθος γραμματοσειράς κειμένου. |
| virtual [FontStyle](../../aspose.svg.rendering/graphiccontext/fontstyle/) { get; set; } | Ορίζει ή λαμβάνει το στυλ γραμματοσειράς κειμένου. |
| virtual [LineCap](../../aspose.svg.rendering/graphiccontext/linecap/) { get; set; } | Ορίζει ή λαμβάνει τον κώδικα που καθορίζει το σχήμα των άκρων για οποιαδήποτε ανοιχτή διαδρομή που σχεδιάζεται. |
| virtual [LineDashOffset](../../aspose.svg.rendering/graphiccontext/linedashoffset/) { get; set; } | Ορίζει ή λαμβάνει την φάση μετατόπισης του τρέχοντος μοτίβου παύλων γραμμής. |
| virtual [LineDashPattern](../../aspose.svg.rendering/graphiccontext/linedashpattern/) { get; set; } | Ορίζει ή λαμβάνει την περιγραφή του μοτίβου παύλων που θα χρησιμοποιηθεί όταν σχεδιάζονται διαδρομές. Μπορεί να οριστεί σε `null` ή σε κενό πίνακα για να απενεργοποιηθεί. |
| virtual [LineJoin](../../aspose.svg.rendering/graphiccontext/linejoin/) { get; set; } | Ορίζει ή λαμβάνει τον κώδικα που καθορίζει το σχήμα των ενώσεων μεταξύ συνδεδεμένων τμημάτων μιας σχεδιασμένης διαδρομής. |
| virtual [LineWidth](../../aspose.svg.rendering/graphiccontext/linewidth/) { get; set; } | Ορίζει ή επιστρέφει το πάχος των διαδρομών που θα σχεδιαστούν. |
| virtual [MiterLimit](../../aspose.svg.rendering/graphiccontext/miterlimit/) { get; set; } | Ορίζει ή επιστρέφει το μέγιστο μήκος των γωνιακών ενώσεων γραμμών για σχεδιασμένες διαδρομές. Αυτή η παράμετρος περιορίζει το μήκος των «ακίδων» που παράγονται όταν τμήματα γραμμής ενώνονται σε οξίες γωνίες. |
| virtual [StrokeBrush](../../aspose.svg.rendering/graphiccontext/strokebrush/) { get; set; } | Ορίζει ή επιστρέφει το αντικείμενο πινέλου που χρησιμοποιείται για σχεδιασμένες διαδρομές. |
| virtual [TextInfo](../../aspose.svg.rendering/graphiccontext/textinfo/) { get; } | Αποκτά ένα αντικείμενο [`TextInfo`](../../aspose.svg.rendering/textinfo/) που περιέχει πληροφορίες σχετικά με το αποδοθέν κείμενο. |
| virtual [TransformationMatrix](../../aspose.svg.rendering/graphiccontext/transformationmatrix/) { get; set; } | Ορίζει ή επιστρέφει τον πίνακα μετασχηματισμού. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| virtual [Clone](../../aspose.svg.rendering/graphiccontext/clone/)() | Δημιουργεί ένα νέο στιγμιότυπο της κλάσης GraphicContext με τις ίδιες τιμές ιδιοτήτων όπως ένα υπάρχον στιγμιότυπο. |
| virtual [Transform](../../aspose.svg.rendering/graphiccontext/transform/)(*[IMatrix](../../aspose.svg.drawing/imatrix/)*) | Τροποποιεί τον τρέχοντα πίνακα μετασχηματισμού πολλαπλασιάζοντας τον καθορισμένο πίνακα. |

### Δείτε επίσης

* class [GraphicContext](../../aspose.svg.rendering/graphiccontext/)
* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Svg.Rendering.Image](../../aspose.svg.rendering.image/)
* assembly [Aspose.SVG](../../)
