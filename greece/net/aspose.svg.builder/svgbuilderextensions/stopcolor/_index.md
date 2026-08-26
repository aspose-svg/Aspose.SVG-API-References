---
title: "SVGBuilderExtensions.StopColor"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος StopColor του SVGBuilderExtensions. Ορίζει το χαρακτηριστικό stop-color για ένα στοιχείο SVG που καθορίζει το χρώμα σε ένα σημείο διαβάθμισης."
type: docs
weight: 2060
url: /el/net/aspose.svg.builder/svgbuilderextensions/stopcolor/
---
## StopColor<TBuilder>(*this TBuilder, Color*) {#stopcolor_1}

Ορίζει το χαρακτηριστικό 'stop-color' για ένα στοιχείο SVG, καθορίζοντας το χρώμα σε ένα σημείο gradient.

```csharp
public static TBuilder StopColor<TBuilder>(this TBuilder builder, Color colorValue)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Η παρουσία του builder. |
| colorValue | Η τιμή χρώματος που θα οριστεί. |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

### Δείτε επίσης

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## StopColor<TBuilder>(*this TBuilder, Action&lt;ColorBuilder&gt;*) {#stopcolor}

Ορίζει το χαρακτηριστικό 'stop-color' για ένα στοιχείο SVG χρησιμοποιώντας προσαρμοσμένη διαμόρφωση χρώματος.

```csharp
public static TBuilder StopColor<TBuilder>(this TBuilder builder, Action<ColorBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Η παρουσία του builder. |
| ρυθμίστε | Ένας αντιπρόσωπος για τη διαμόρφωση του χρώματος. |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

### Δείτε επίσης

* class [ColorBuilder](../../colorbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
