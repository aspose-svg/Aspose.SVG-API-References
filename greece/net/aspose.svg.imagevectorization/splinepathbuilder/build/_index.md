---
title: "SplinePathBuilder.Build"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος Build του SplinePathBuilder. Δημιουργεί μια ομαλή διαδρομή μέσω μιας ακολουθίας σημείων μετατρέποντας τις κεντρικές CatmullRom καμπύλες σε καμπύλες Bezier. Αυτή η μέθοδος εξασφαλίζει μια φυσική και ομαλή μετάβαση σε κάθε σημείο δημιουργώντας μια διαδρομή SVG που ακολουθεί στενά το παρεχόμενο trace."
type: docs
weight: 50
url: /el/net/aspose.svg.imagevectorization/splinepathbuilder/build/
---
## SplinePathBuilder.Build method

Δημιουργεί μια ομαλή διαδρομή μέσω μιας ακολουθίας σημείων μετατρέποντας τις σπείρες Centripetal Catmull–Rom σε καμπύλες Bezier. Αυτή η μέθοδος εξασφαλίζει μια φυσική και ομαλή μετάβαση σε κάθε σημείο, δημιουργώντας μια διαδρομή SVG που ακολουθεί στενά το παρεχόμενο ίχνος.

```csharp
public string Build(IEnumerable<PointF> trace)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ίχνος | IEnumerable`1 | Η ακολουθία των σημείων που θα παρεμβληθούν σε μια ομαλή διαδρομή. |

### Τιμή Επιστροφής

Μια συμβολοσειρά που αντιπροσωπεύει τα δεδομένα διαδρομής SVG, περιλαμβάνοντας εντολές καμπύλης Bezier και συντεταγμένες που προσεγγίζουν την κεντρική Catmull–Rom καμπύλη.

### Δείτε επίσης

* class [SplinePathBuilder](../)
* namespace [Aspose.Svg.ImageVectorization](../../../aspose.svg.imagevectorization/)
* assembly [Aspose.SVG](../../../)
