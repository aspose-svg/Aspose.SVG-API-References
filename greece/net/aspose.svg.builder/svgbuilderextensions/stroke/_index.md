---
title: "SVGBuilderExtensions.Stroke"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Μέθοδος Stroke του SVGBuilderExtensions. Ορίζει το χαρακτηριστικό stroke για ένα στοιχείο SVG χρησιμοποιώντας προσαρμοσμένη διαμόρφωση χρώματος."
type: docs
weight: 2080
url: /el/net/aspose.svg.builder/svgbuilderextensions/stroke/
---
## Stroke<TBuilder>(*this TBuilder, Action&lt;PaintBuilder&gt;*) {#stroke_1}

Ορίζει το χαρακτηριστικό 'stroke' για ένα στοιχείο SVG χρησιμοποιώντας προσαρμοσμένη διαμόρφωση βαφής.

```csharp
public static TBuilder Stroke<TBuilder>(this TBuilder builder, Action<PaintBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Η παρουσία του builder. |
| ρυθμίστε | Ένας delegate για τη διαμόρφωση του χρώματος. |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

### Δείτε επίσης

* class [PaintBuilder](../../paintbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Stroke<TBuilder>(*this TBuilder, Color*) {#stroke_2}

Ορίζει το χαρακτηριστικό 'stroke' για ένα στοιχείο SVG χρησιμοποιώντας συγκεκριμένο χρώμα.

```csharp
public static TBuilder Stroke<TBuilder>(this TBuilder builder, Color color)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Η παρουσία του builder. |
| χρώμα | Το χρώμα που θα χρησιμοποιηθεί για το stroke. |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

### Δείτε επίσης

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Stroke<TBuilder>(*this TBuilder, [Paint](../../paint/)*) {#stroke}

Ορίζει το χαρακτηριστικό 'stroke' για ένα στοιχείο SVG χρησιμοποιώντας προεπιλεγμένη τιμή βαφής.

```csharp
public static TBuilder Stroke<TBuilder>(this TBuilder builder, Paint paint)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TBuilder | Ο τύπος του builder στοιχείου SVG. |
| builder | Η παρουσία του builder. |
| βάψιμο | Η τιμή χρώματος που θα οριστεί. |

### Τιμή Επιστροφής

Η παρουσία του builder για αλυσίδωση.

### Δείτε επίσης

* enum [Paint](../../paint/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
