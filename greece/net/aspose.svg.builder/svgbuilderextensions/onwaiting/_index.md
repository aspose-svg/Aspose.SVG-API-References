---
title: "SVGBuilderExtensions.OnWaiting"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "SVGBuilderExtensions OnWaiting μέθοδος. Ορίζει το χαρακτηριστικό onwaiting για τη διαχείριση συμβάντων όταν η αναπαραγωγή πολυμέσων καθυστερεί λόγω προσωρινής αποθήκευσης δεδομένων"
type: docs
weight: 1850
url: /el/net/aspose.svg.builder/svgbuilderextensions/onwaiting/
---
## SVGBuilderExtensions.OnWaiting<TBuilder> method

Ορίζει το χαρακτηριστικό συμβάντος 'onwaiting' για τη διαχείριση των συμβάντων όταν η αναπαραγωγή πολυμέσων καθυστερεί λόγω προσωρινής αποθήκευσης δεδομένων.

```csharp
public static TBuilder OnWaiting<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Ο builder στοιχείου SVG. |
| τιμή | Η συνάρτηση JavaScript ή το script που εκτελείται όταν η αναπαραγωγή μέσου καθυστερεί λόγω buffering. |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

### Δείτε επίσης

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
