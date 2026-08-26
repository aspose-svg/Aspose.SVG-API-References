---
title: "SVGBuilderExtensions.TextDecoration"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος SVGBuilderExtensions TextDecoration. Ορίζει το χαρακτηριστικό text-decoration για ένα στοιχείο SVG που ορίζει διακοσμήσεις που προστίθενται στο κείμενο."
type: docs
weight: 2210
url: /el/net/aspose.svg.builder/svgbuilderextensions/textdecoration/
---
## SVGBuilderExtensions.TextDecoration<TBuilder> method

Ορίζει το χαρακτηριστικό 'text-decoration' για ένα στοιχείο SVG, ορίζοντας τις διακοσμήσεις που προστίθενται στο κείμενο.

```csharp
public static TBuilder TextDecoration<TBuilder>(this TBuilder builder, bool underline = false, 
    bool overline = false, bool lineThrough = false, bool blink = false)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Η παρουσία του builder. |
| underline | Καθορίζει αν το κείμενο πρέπει να είναι υπογραμμισμένο. |
| overline | Καθορίζει αν το κείμενο πρέπει να έχει γραμμή πάνω από αυτό. |
| lineThrough | Καθορίζει εάν το κείμενο πρέπει να έχει γραμμή διαγραφής. |
| αναβόσβημα | Καθορίζει εάν το κείμενο πρέπει να αναβοσβήνει (δεν συνιστάται για χρήση). |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

### Δείτε επίσης

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
