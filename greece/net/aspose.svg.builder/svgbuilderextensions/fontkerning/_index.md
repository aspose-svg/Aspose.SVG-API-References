---
title: "SVGBuilderExtensions.FontKerning"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "SVGBuilderExtensions FontKerning μέθοδος. Ορίζει το χαρακτηριστικό font-kerning για ένα στοιχείο SVG χρησιμοποιώντας μια αριθμητική τιμή και έναν συγκεκριμένο τύπο μήκους."
type: docs
weight: 880
url: /el/net/aspose.svg.builder/svgbuilderextensions/fontkerning/
---
## FontKerning<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#fontkerning_1}

Ορίζει το χαρακτηριστικό 'font-kerning' για ένα στοιχείο SVG χρησιμοποιώντας μια αριθμητική τιμή και έναν συγκεκριμένο τύπο μήκους.

```csharp
public static TBuilder FontKerning<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Η παρουσία του builder. |
| τιμή | Η τιμή του font kerning που θα οριστεί. |
| type | Ο τύπος μήκους (π.χ., px, em). |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

### Δείτε επίσης

* enum [LengthType](../../lengthtype/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## FontKerning<TBuilder>(*this TBuilder, [Kerning](../../kerning/)*) {#fontkerning}

Ορίζει το χαρακτηριστικό 'font-kerning' για ένα στοιχείο SVG χρησιμοποιώντας μια προεπιλεγμένη τιμή kerning.

```csharp
public static TBuilder FontKerning<TBuilder>(this TBuilder builder, Kerning value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Η παρουσία του builder. |
| τιμή | Η προεπιλεγμένη τιμή kerning που θα οριστεί. |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

### Δείτε επίσης

* enum [Kerning](../../kerning/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
