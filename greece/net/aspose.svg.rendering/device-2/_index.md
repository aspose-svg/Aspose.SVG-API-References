---
title: "DeviceTGraphicContextTRenderingOptions Κλάση"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Aspose.Svg.Rendering.Device2TGraphicContextTRenderingOptions κλάση. Αντιπροσωπεύει τη βασική κλάση για την υλοποίηση συγκεκριμένων συσκευών απόδοσης"
type: docs
weight: 4820
url: /el/net/aspose.svg.rendering/device-2/
---
## Device<TGraphicContext,TRenderingOptions> class

Αναπαριστά τη βασική κλάση για την υλοποίηση συγκεκριμένων συσκευών απόδοσης.

```csharp
public abstract class Device<TGraphicContext, TRenderingOptions> : Device, IDevice
    where TGraphicContext : GraphicContext, new()
    where TRenderingOptions : RenderingOptions
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TGraphicContext | Πλαίσιο γραφικών που κρατά τις τρέχουσες παραμέτρους ελέγχου γραφικών |
| TRenderingOptions | Επιλογές απόδοσης |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [GraphicContext](../../aspose.svg.rendering/device-2/graphiccontext/) { get; } | Αποκτά το πλαίσιο γραφικών |
| [Options](../../aspose.svg.rendering/device-2/options/) { get; } | Λαμβάνει τις επιλογές απόδοσης. |
| virtual [Configuration](../../aspose.svg.rendering/device-2/configuration/) { get; } | Αποκτά τη διαμόρφωση της συσκευής. |
| [OutputStream](../../aspose.svg.rendering/device-2/outputstream/) { get; } | Ορίζει και λαμβάνει τη ροή εξόδου. |
| [StreamProvider](../../aspose.svg.rendering/device-2/streamprovider/) { get; } | Λαμβάνει το αντικείμενο παρόχου ροής. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| virtual [AddRect](../../aspose.svg.rendering/device-2/addrect/)(*RectangleF*) | Προσθέτει ένα ορθογώνιο στην τρέχουσα διαδρομή ως πλήρη υποδιαδρομή. |
| virtual [BeginDocument](../../aspose.svg.rendering/device-2/begindocument/)(*[Document](../../aspose.svg.dom/document/)*) | Ξεκινά την απόδοση του εγγράφου. |
| virtual [BeginElement](../../aspose.svg.rendering/device-2/beginelement/)(*[Element](../../aspose.svg.dom/element/), RectangleF*) | Ξεκινά την απόδοση του κόμβου. |
| virtual [BeginPage](../../aspose.svg.rendering/device-2/beginpage/)(*SizeF*) | Ξεκινά την απόδοση της νέας σελίδας. |
| virtual [Clip](../../aspose.svg.rendering/device-2/clip/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | Τροποποιεί την τρέχουσα διαδρομή αποκοπής διασταυρώνοντάς την με την τρέχουσα διαδρομή, χρησιμοποιώντας τον FillRule για να καθορίσει την περιοχή που θα γεμίσει. Αυτή η μέθοδος τερματίζει την τρέχουσα διαδρομή. |
| virtual [ClosePath](../../aspose.svg.rendering/device-2/closepath/)() | Κλείνει την τρέχουσα υποδιαδρομή προσθέτοντας ένα ευθύγραμμο τμήμα από το τρέχον σημείο στο αρχικό σημείο της υποδιαδρομής. Εάν η τρέχουσα υποδιαδρομή είναι ήδη κλειστή, το "ClosePath" δεν κάνει τίποτα. Αυτός ο τελεστής τερματίζει την τρέχουσα υποδιαδρομή. Η προσθήκη ενός άλλου τμήματος στην τρέχουσα διαδρομή ξεκινά μια νέα υποδιαδρομή, ακόμη και αν το νέο τμήμα ξεκινά στο σημείο λήξης που επιτεύχθηκε από τη μέθοδο "ClosePath". |
| virtual [CubicBezierTo](../../aspose.svg.rendering/device-2/cubicbezierto/)(*PointF, PointF, PointF*) | Προσθέτει μια κυβική καμπύλη Bézier στην τρέχουσα διαδρομή. Η καμπύλη εκτείνεται από το τρέχον σημείο έως το σημείο pt2, χρησιμοποιώντας τα pt1 και pt2 ως σημεία ελέγχου Bézier. Το νέο τρέχον σημείο είναι pt3. |
| [Dispose](../../aspose.svg.rendering/device-2/dispose/)() | Εκτελεί εργασίες που ορίζονται από την εφαρμογή και σχετίζονται με την απελευθέρωση, την αποδέσμευση ή την επαναφορά μη διαχειριζόμενων πόρων. |
| virtual [DrawImage](../../aspose.svg.rendering/device-2/drawimage/)(*byte[], [WebImageFormat](../../aspose.svg.drawing/webimageformat/), RectangleF*) | Σχεδιάζει την καθορισμένη εικόνα. |
| virtual [EndDocument](../../aspose.svg.rendering/device-2/enddocument/)() | Τελειώνει την απόδοση του εγγράφου. |
| virtual [EndElement](../../aspose.svg.rendering/device-2/endelement/)(*[Element](../../aspose.svg.dom/element/)*) | Τελειώνει την απόδοση του κόμβου. |
| virtual [EndPage](../../aspose.svg.rendering/device-2/endpage/)() | Τελειώνει την απόδοση της τρέχουσας σελίδας. |
| virtual [Fill](../../aspose.svg.rendering/device-2/fill/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | Γεμίζει ολόκληρη την περιοχή που περιβάλλεται από την τρέχουσα διαδρομή. Εάν η διαδρομή αποτελείται από πολλές αποσυνδεδεμένες υποδιαδρομές, γεμίζει τα εσωτερικά όλων των υποδιαδρομών, θεωρημένα μαζί. Αυτή η μέθοδος τερματίζει την τρέχουσα διαδρομή. |
| virtual [FillText](../../aspose.svg.rendering/device-2/filltext/)(*string, PointF*) | Γεμίζει την καθορισμένη συμβολοσειρά κειμένου στην καθορισμένη θέση. |
| virtual [Flush](../../aspose.svg.rendering/device-2/flush/)() | Αδειάζει όλα τα δεδομένα στο ρεύμα εξόδου. |
| virtual [LineTo](../../aspose.svg.rendering/device-2/lineto/)(*PointF*) | Προσθέτει ένα ευθύ τμήμα γραμμής από το τρέχον σημείο στο σημείο (pt). Το νέο τρέχον σημείο είναι το pt. |
| virtual [MoveTo](../../aspose.svg.rendering/device-2/moveto/)(*PointF*) | Ξεκινά ένα νέο υπο‑σχέδιο μετακινώντας το τρέχον σημείο στις συντεταγμένες της παραμέτρου pt, παραλείποντας οποιοδήποτε συνδετικό τμήμα γραμμής. Εάν η προηγούμενη μέθοδος κατασκευής διαδρομής στο τρέχον σχέδιο ήταν επίσης "MoveTo", το νέο "MoveTo" την αντικαθιστά· δεν απομένει κανένα ίχνος της προηγούμενης λειτουργίας "MoveTo" στη διαδρομή. |
| virtual [RestoreGraphicContext](../../aspose.svg.rendering/device-2/restoregraphiccontext/)() | Επαναφέρει ολόκληρο το πλαίσιο γραφικών στην προηγούμενη τιμή του αφαιρώντας το από τη στοίβα. |
| virtual [SaveGraphicContext](../../aspose.svg.rendering/device-2/savegraphiccontext/)() | Τοποθετεί ένα αντίγραφο ολόκληρου του πλαισίου γραφικών στη στοίβα. |
| virtual [Stroke](../../aspose.svg.rendering/device-2/stroke/)() | Σχεδιάζει μια γραμμή κατά μήκος του τρέχοντος μονοπατιού. Η σχεδιασμένη γραμμή ακολουθεί κάθε ευθύ ή καμπυλωτό τμήμα του μονοπατιού, κεντραρισμένη στο τμήμα με πλευρές παράλληλες σε αυτό. Κάθε υπο‑μονοπάτι του μονοπατιού αντιμετωπίζεται ξεχωριστά. Αυτή η μέθοδος τερματίζει το τρέχον μονοπάτι. |
| virtual [StrokeAndFill](../../aspose.svg.rendering/device-2/strokeandfill/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | Σχεδιάζει και γεμίζει το τρέχον μονοπάτι. Αυτή η μέθοδος τερματίζει το τρέχον μονοπάτι. |
| virtual [StrokeText](../../aspose.svg.rendering/device-2/stroketext/)(*string, PointF*) | Σχεδιάζει την καθορισμένη συμβολοσειρά κειμένου στην καθορισμένη θέση. |

## Άλλα Μέλη

| Όνομα | Περιγραφή |
| --- | --- |
| class [DeviceConfiguration<TGraphicContext,TRenderingOptions>](../../aspose.svg.rendering/device-2.deviceconfiguration-2) | Αντιπροσωπεύει αντικείμενο διαμόρφωσης για συσκευές. |
| enum [PageWritingStrategy<TGraphicContext,TRenderingOptions>](../../aspose.svg.rendering/device-2.pagewritingstrategy-2) | Καθορίζει τύπους στρατηγικών για τη γραφή σελίδων σε ρεύμα\streams. |

### Δείτε επίσης

* class [Device](../device/)
* interface [IDevice](../idevice/)
* class [GraphicContext](../graphiccontext/)
* class [RenderingOptions](../renderingoptions/)
* namespace [Aspose.Svg.Rendering](../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../)
