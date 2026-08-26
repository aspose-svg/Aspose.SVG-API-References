---
title: "SplinePathBuilder Κλάση"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Η κλάση Aspose.Svg.ImageVectorization.SplinePathBuilder. Η κλάση SplinePathBuilder έχει σχεδιαστεί για να κατασκευάσει μια ομαλή διαδρομή μετατρέποντας τις κεντρικές σπλάχνες CatmullRom σε καμπύλες Bezier. Προσφέρει μια μέθοδο για τη δημιουργία μιας διαδρομής που παρεμβάλλεται ομαλά μέσω ενός συνόλου σημείων, παρέχοντας μια ισορροπία μεταξύ της πιστότητας στα σημεία και της ομαλότητας της καμπύλης."
type: docs
weight: 4230
url: /el/net/aspose.svg.imagevectorization/splinepathbuilder/
---
## SplinePathBuilder class

Η κλάση `SplinePathBuilder` έχει σχεδιαστεί για να κατασκευάσει μια ομαλή διαδρομή μετατρέποντας τις κεντρικές σπλάχνες Catmull–Rom σε καμπύλες Bezier. Προσφέρει μια μέθοδο για τη δημιουργία μιας διαδρομής που παρεμβάλλεται ομαλά μέσω ενός συνόλου σημείων, παρέχοντας μια ισορροπία μεταξύ της πιστότητας στα σημεία και της ομαλότητας της καμπύλης.

```csharp
public class SplinePathBuilder : IPathBuilder
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [SplinePathBuilder](splinepathbuilder/#constructor)() | Αρχικοποιεί μια νέα παρουσία της κλάσης `SplinePathBuilder`. |
| [SplinePathBuilder](splinepathbuilder/#constructor_2)(*float*) | Αρχικοποιεί μια νέα παρουσία της κλάσης `SplinePathBuilder`. |
| [SplinePathBuilder](splinepathbuilder/#constructor_1)(*[IImageTraceSmoother](../iimagetracesmoother/), [IImageTraceSimplifier](../iimagetracesimplifier/), float*) | Αρχικοποιεί μια νέα παρουσία της κλάσης `SplinePathBuilder`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Tension](../../aspose.svg.imagevectorization/splinepathbuilder/tension/) { get; set; } | Η τιμή των τάσεων επηρεάζει πόσο απότομα λυγίζει η καμπύλη στα (διαμεσολαβημένα) σημεία ελέγχου. Πρέπει να βρίσκεται στο εύρος από 0 έως 1. Οποιεσδήποτε υψηλότερες ή χαμηλότερες τιμές θα ευθυγραμμιστούν με τις ελάχιστες και μέγιστες τιμές αυτού του εύρους, αντίστοιχα. |
| [TraceSimplifier](../../aspose.svg.imagevectorization/splinepathbuilder/tracesimplifier/) { get; set; } | Λαμβάνει ή ορίζει τον απλοποιητή του ίχνους. |
| [TraceSmoother](../../aspose.svg.imagevectorization/splinepathbuilder/tracesmoother/) { get; set; } | Λαμβάνει ή ορίζει τον εξομαλυντή του ίχνους. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Build](../../aspose.svg.imagevectorization/splinepathbuilder/build/)(*IEnumerable&lt;PointF&gt;*) | Δημιουργεί μια ομαλή διαδρομή μέσω μιας ακολουθίας σημείων μετατρέποντας τις σπείρες Centripetal Catmull–Rom σε καμπύλες Bezier. Αυτή η μέθοδος εξασφαλίζει μια φυσική και ομαλή μετάβαση σε κάθε σημείο, δημιουργώντας μια διαδρομή SVG που ακολουθεί στενά το παρεχόμενο ίχνος. |

### Δείτε επίσης

* interface [IPathBuilder](../ipathbuilder/)
* namespace [Aspose.Svg.ImageVectorization](../../aspose.svg.imagevectorization/)
* assembly [Aspose.SVG](../../)
