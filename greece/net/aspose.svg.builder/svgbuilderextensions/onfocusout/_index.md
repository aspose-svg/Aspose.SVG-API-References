---
title: "SVGBuilderExtensions.OnFocusOut"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος SVGBuilderExtensions OnFocusOut. Ορίζει το χαρακτηριστικό συμβάντος onfocusout για τη διαχείριση συμβάντων απομάκρυνσης εστίασης στο στοιχείο."
type: docs
weight: 1460
url: /el/net/aspose.svg.builder/svgbuilderextensions/onfocusout/
---
## SVGBuilderExtensions.OnFocusOut<TBuilder> method

Ορίζει το χαρακτηριστικό συμβάντος 'onfocusout' για τη διαχείριση των γεγονότων εστίασης-εξόδου στο στοιχείο.

```csharp
public static TBuilder OnFocusOut<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGraphicalEventAttributeSetter
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Ο builder στοιχείου SVG. |
| τιμή | Η λειτουργία ή το σενάριο JavaScript που εκτελείται όταν το στοιχείο χάνει την εστίαση, συνήθως πριν το συμβάν 'onblur'. |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

## Παρατηρήσεις

Το συμβάν 'onfocusout' ενεργοποιείται όταν ένα στοιχείο πρόκειται να χάσει την εστίαση. Παρόμοιο με το 'onfocusin', αυτό το συμβάν υποστηρίζει την διάδοση (bubbling) και μπορεί επίσης να χρησιμοποιηθεί για την ανίχνευση αλλαγών εστίασης σε θυγατρικά στοιχεία.

### Δείτε επίσης

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGraphicalEventAttributeSetter](../../igraphicaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
