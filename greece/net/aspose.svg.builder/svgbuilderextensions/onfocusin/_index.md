---
title: "SVGBuilderExtensions.OnFocusIn"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος SVGBuilderExtensions OnFocusIn. Ορίζει το χαρακτηριστικό συμβάντος onfocusin για τη διαχείριση των γεγονότων εστίασης-εντός στο στοιχείο."
type: docs
weight: 1450
url: /el/net/aspose.svg.builder/svgbuilderextensions/onfocusin/
---
## SVGBuilderExtensions.OnFocusIn<TBuilder> method

Ορίζει το χαρακτηριστικό συμβάντος 'onfocusin' για τη διαχείριση των γεγονότων εστίασης-εισόδου στο στοιχείο.

```csharp
public static TBuilder OnFocusIn<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGraphicalEventAttributeSetter
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Ο builder στοιχείου SVG. |
| τιμή | Η λειτουργία ή το σενάριο JavaScript που εκτελείται όταν το στοιχείο λαμβάνει εστίαση, συνήθως πριν από το συμβάν 'onfocus'. |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

## Παρατηρήσεις

Το συμβάν 'onfocusin' ενεργοποιείται όταν ένα στοιχείο πρόκειται να λάβει εστίαση. Αυτό το συμβάν διαφέρει από το 'onfocus' επειδή υποστηρίζει διάδοση (bubbling) και μπορεί να χρησιμοποιηθεί για την ανίχνευση αλλαγών εστίασης και σε θυγατρικά στοιχεία.

### Δείτε επίσης

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGraphicalEventAttributeSetter](../../igraphicaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
