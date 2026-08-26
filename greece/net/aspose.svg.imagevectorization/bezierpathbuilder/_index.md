---
title: "BezierPathBuilder Κλάση"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Aspose.Svg.ImageVectorization.BezierPathBuilder κλάση. Η κλάση BezierPathBuilder είναι υπεύθυνη για την κατασκευή μιας διαδρομής Bezier από ένα δεδομένο σύνολο σημείων. Προσεγγίζει ένα ίχνος σημείων με μια καμπύλη Bezier βελτιστοποιώντας τον αριθμό των τμημάτων ώστε να ταιριάζει στενά με το αρχικό ίχνος, ελαχιστοποιώντας την πολυπλοκότητα"
type: docs
weight: 4150
url: /el/net/aspose.svg.imagevectorization/bezierpathbuilder/
---
## BezierPathBuilder class

Η κλάση `BezierPathBuilder` είναι υπεύθυνη για την κατασκευή μιας διαδρομής Bezier από ένα δεδομένο σύνολο σημείων. Προσεγγίζει ένα ίχνος σημείων με μια καμπύλη Bezier, βελτιστοποιώντας τον αριθμό των τμημάτων ώστε να ταιριάζει στενά με το αρχικό ίχνος, ελαχιστοποιώντας την πολυπλοκότητα.

```csharp
public class BezierPathBuilder : IPathBuilder
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [BezierPathBuilder](bezierpathbuilder/)() | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `BezierPathBuilder`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [ErrorThreshold](../../aspose.svg.imagevectorization/bezierpathbuilder/errorthreshold/) { get; set; } | Λαμβάνει ή ορίζει το όριο σφάλματος. Αυτή η παράμετρος ορίζει τη μέγιστη απόκλιση των σημείων από την προσαρμοσμένη καμπύλη. Από προεπιλογή είναι 30. |
| [MaxIterations](../../aspose.svg.imagevectorization/bezierpathbuilder/maxiterations/) { get; set; } | Λαμβάνει ή ορίζει το όριο σφάλματος. Αυτή η παράμετρος ορίζει τον αριθμό των επαναλήψεων για τη μέθοδο προσέγγισης ελαχίστων τετραγώνων. Από προεπιλογή είναι 30. |
| [TraceSmoother](../../aspose.svg.imagevectorization/bezierpathbuilder/tracesmoother/) { get; set; } | Λαμβάνει ή ορίζει τον εξομαλυντή του ίχνους. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Build](../../aspose.svg.imagevectorization/bezierpathbuilder/build/)(*IEnumerable&lt;PointF&gt;*) | Δημιουργεί μια βελτιστοποιημένη διαδρομή Bezier από μια ακολουθία σημείων ίχνους. Η μέθοδος προσεγγίζει το δεδομένο ίχνος με μια καμπύλη Bezier, χρησιμοποιώντας συνδυασμό τμημάτων γραμμής και καμπύλης. Στοχεύει στη μείωση του αριθμού των τμημάτων διασφαλίζοντας ταυτόχρονα ότι η διαδρομή ταιριάζει στενά με το αρχικό ίχνος. |

### Δείτε επίσης

* interface [IPathBuilder](../ipathbuilder/)
* namespace [Aspose.Svg.ImageVectorization](../../aspose.svg.imagevectorization/)
* assembly [Aspose.SVG](../../)
