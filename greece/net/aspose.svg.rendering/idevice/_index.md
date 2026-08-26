---
title: "IDevice Interface"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Aspose.Svg.Rendering.IDevice interface. Ορίζει μεθόδους και ιδιότητες που υποστηρίζουν προσαρμοστική απόδοση των γραφικών στοιχείων όπως μονοπάτια, κείμενο και εικόνες"
type: docs
weight: 4890
url: /el/net/aspose.svg.rendering/idevice/
---
## IDevice interface

Ορίζει μεθόδους και ιδιότητες που υποστηρίζουν προσαρμοσμένη απόδοση των γραφικών στοιχείων όπως διαδρομές, κείμενο και εικόνες.

```csharp
public interface IDevice : IDisposable
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [GraphicContext](../../aspose.svg.rendering/idevice/graphiccontext/) { get; } | Λαμβάνει το γραφικό περιβάλλον. |
| [Options](../../aspose.svg.rendering/idevice/options/) { get; } | Λαμβάνει τις επιλογές απόδοσης. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddRect](../../aspose.svg.rendering/idevice/addrect/)(*RectangleF*) | Προσθέτει ένα ορθογώνιο στην τρέχουσα διαδρομή ως πλήρη υποδιαδρομή. |
| [BeginDocument](../../aspose.svg.rendering/idevice/begindocument/)(*[Document](../../aspose.svg.dom/document/)*) | Ξεκινά την απόδοση του εγγράφου. |
| [BeginElement](../../aspose.svg.rendering/idevice/beginelement/)(*[Element](../../aspose.svg.dom/element/), RectangleF*) | Ξεκινά την απόδοση του στοιχείου. |
| [BeginPage](../../aspose.svg.rendering/idevice/beginpage/)(*SizeF*) | Ξεκινά την απόδοση της νέας σελίδας. |
| [Clip](../../aspose.svg.rendering/idevice/clip/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | Τροποποιεί την τρέχουσα διαδρομή αποκοπής διασταυρώνοντάς την με την τρέχουσα διαδρομή, χρησιμοποιώντας τον FillRule για να καθορίσει την περιοχή που θα γεμίσει. Αυτή η μέθοδος τερματίζει την τρέχουσα διαδρομή. |
| [ClosePath](../../aspose.svg.rendering/idevice/closepath/)() | Κλείνει την τρέχουσα υποδιαδρομή προσθέτοντας ένα ευθύγραμμο τμήμα από το τρέχον σημείο στο αρχικό σημείο της υποδιαδρομής. Εάν η τρέχουσα υποδιαδρομή είναι ήδη κλειστή, το "ClosePath" δεν κάνει τίποτα. Αυτός ο τελεστής τερματίζει την τρέχουσα υποδιαδρομή. Η προσθήκη ενός άλλου τμήματος στην τρέχουσα διαδρομή ξεκινά μια νέα υποδιαδρομή, ακόμη και αν το νέο τμήμα ξεκινά στο σημείο λήξης που επιτεύχθηκε από τη μέθοδο "ClosePath". |
| [CubicBezierTo](../../aspose.svg.rendering/idevice/cubicbezierto/)(*PointF, PointF, PointF*) | Προσθέτει μια κυβική καμπύλη Bézier στην τρέχουσα διαδρομή. Η καμπύλη εκτείνεται από το τρέχον σημείο έως το σημείο pt3, χρησιμοποιώντας τα pt1 και pt2 ως σημεία ελέγχου Bézier. Το νέο τρέχον σημείο είναι το pt3. |
| [DrawImage](../../aspose.svg.rendering/idevice/drawimage/)(*byte[], [WebImageFormat](../../aspose.svg.drawing/webimageformat/), RectangleF*) | Σχεδιάζει την καθορισμένη εικόνα. |
| [EndDocument](../../aspose.svg.rendering/idevice/enddocument/)() | Τελειώνει την απόδοση του εγγράφου. |
| [EndElement](../../aspose.svg.rendering/idevice/endelement/)(*[Element](../../aspose.svg.dom/element/)*) | Τελειώνει την απόδοση του στοιχείου. |
| [EndPage](../../aspose.svg.rendering/idevice/endpage/)() | Τελειώνει την απόδοση της τρέχουσας σελίδας. |
| [Fill](../../aspose.svg.rendering/idevice/fill/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | Γεμίζει ολόκληρη την περιοχή που περιβάλλεται από την τρέχουσα διαδρομή. Εάν η διαδρομή αποτελείται από πολλές αποσυνδεδεμένες υποδιαδρομές, γεμίζει τα εσωτερικά όλων των υποδιαδρομών, θεωρημένα μαζί. Αυτή η μέθοδος τερματίζει την τρέχουσα διαδρομή. |
| [FillText](../../aspose.svg.rendering/idevice/filltext/)(*string, PointF*) | Γεμίζει την καθορισμένη συμβολοσειρά κειμένου στην καθορισμένη θέση. |
| [Flush](../../aspose.svg.rendering/idevice/flush/)() | Αδειάζει όλα τα δεδομένα στο ρεύμα εξόδου. |
| [LineTo](../../aspose.svg.rendering/idevice/lineto/)(*PointF*) | Προσθέτει ένα ευθύ τμήμα γραμμής από το τρέχον σημείο στο σημείο (pt). Το νέο τρέχον σημείο είναι το pt. |
| [MoveTo](../../aspose.svg.rendering/idevice/moveto/)(*PointF*) | Ξεκινά ένα νέο υπο‑σχέδιο μετακινώντας το τρέχον σημείο στις συντεταγμένες της παραμέτρου pt, παραλείποντας οποιοδήποτε συνδετικό τμήμα γραμμής. Εάν η προηγούμενη μέθοδος κατασκευής διαδρομής στο τρέχον σχέδιο ήταν επίσης "MoveTo", το νέο "MoveTo" την αντικαθιστά· δεν απομένει κανένα ίχνος της προηγούμενης λειτουργίας "MoveTo" στη διαδρομή. |
| [RestoreGraphicContext](../../aspose.svg.rendering/idevice/restoregraphiccontext/)() | Επαναφέρει ολόκληρο το πλαίσιο γραφικών στην προηγούμενη τιμή του αφαιρώντας το από τη στοίβα. |
| [SaveGraphicContext](../../aspose.svg.rendering/idevice/savegraphiccontext/)() | Τοποθετεί ένα αντίγραφο ολόκληρου του πλαισίου γραφικών στη στοίβα. |
| [Stroke](../../aspose.svg.rendering/idevice/stroke/)() | Σχεδιάζει μια γραμμή κατά μήκος του τρέχοντος μονοπατιού. Η σχεδιασμένη γραμμή ακολουθεί κάθε ευθύ ή καμπυλωτό τμήμα του μονοπατιού, κεντραρισμένη στο τμήμα με πλευρές παράλληλες σε αυτό. Κάθε υπο‑μονοπάτι του μονοπατιού αντιμετωπίζεται ξεχωριστά. Αυτή η μέθοδος τερματίζει το τρέχον μονοπάτι. |
| [StrokeAndFill](../../aspose.svg.rendering/idevice/strokeandfill/)(*[FillRule](../../aspose.svg.drawing/fillrule/)*) | Σχεδιάζει και γεμίζει το τρέχον μονοπάτι. Αυτή η μέθοδος τερματίζει το τρέχον μονοπάτι. |
| [StrokeText](../../aspose.svg.rendering/idevice/stroketext/)(*string, PointF*) | Σχεδιάζει την καθορισμένη συμβολοσειρά κειμένου στην καθορισμένη θέση. |

### Δείτε επίσης

* namespace [Aspose.Svg.Rendering](../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../)
