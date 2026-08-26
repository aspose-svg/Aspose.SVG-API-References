---
title: "SVGElementBuilderT Class"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Aspose.Svg.Builder.SVGElementBuilder1T class. Αντιπροσωπεύει μια βασική κλάση για τη δημιουργία στοιχείων SVG τύπου T"
type: docs
weight: 1160
url: /el/net/aspose.svg.builder/svgelementbuilder-1/
---
## SVGElementBuilder<T> class

Αντιπροσωπεύει μια βασική κατηγορία για τη δημιουργία στοιχείων SVG τύπου *T*.

```csharp
public abstract class SVGElementBuilder<T> : ISVGElementBuilder
    where T : SVGElement
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος του στοιχείου SVG για τον οποίο αυτός ο builder είναι υπεύθυνος για τη δημιουργία. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } | Αποκτά τη λίστα των ρυθμίσεων που θα εφαρμοστούν στο στοιχείο SVG. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) | Προσθέτει μια ρύθμιση ιδιότητας στο στοιχείο SVG. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/#build)(*[Document](../../aspose.svg.dom/document/)*) | Δημιουργεί το στοιχείο SVG και εφαρμόζει όλες τις ρυθμίσεις σε αυτό. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/#build_1)(*T*) | Εφαρμόζει ρυθμίσεις σε ένα υπάρχον στοιχείο SVG. |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) | Δημιουργεί το στοιχείο SVG ως ένα γενικό SVGElement. |

### Δείτε επίσης

* interface [ISVGElementBuilder](../isvgelementbuilder/)
* class [SVGElement](../../aspose.svg/svgelement/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
