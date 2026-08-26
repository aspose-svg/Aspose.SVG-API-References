---
title: "SVGFEBaseLightingElementBuilderTElementTBuilder Κλάση"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Aspose.Svg.Builder.SVGFEBaseLightingElementBuilder2TElementTBuilder κλάση. Αφηρημένη βασική κλάση για δημιουργούς στοιχείων φωτισμού εφέ φίλτρου SVG"
type: docs
weight: 1180
url: /el/net/aspose.svg.builder/svgfebaselightingelementbuilder-2/
---
## SVGFEBaseLightingElementBuilder<TElement,TBuilder> class

Αφηρημένη βασική κατηγορία για builders στοιχείων φωτισμού εφέ φίλτρων SVG.

```csharp
public abstract class SVGFEBaseLightingElementBuilder<TElement, TBuilder> : 
    SVGElementBuilder<TElement>, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IFilterPrimitiveInAttributeSetter, IPresentationAttributeSetter
    where TElement : SVGElement
    where TBuilder : SVGFEBaseLightingElementBuilder
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| TElement | Ο τύπος του στοιχείου SVG που κατασκευάζεται. |
| TBuilder | Ο τύπος του δημιουργού καθαυτό. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | Προσθέτει μια ρύθμιση σεναρίου στο στοιχείο. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| override [Build](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/build/#build)(*[Document](../../aspose.svg.dom/document/)*) | Κατασκευάζει το στοιχείο SVG, εφαρμόζοντας τη ρύθμιση της πηγής φωτός εάν έχει καθοριστεί. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*TElement*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [WithFeDistantLight](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/withfedistantlight/)(*Action&lt;SVGFEDistantLightElementBuilder&gt;*) | Διαμορφώνει μια απομακρυσμένη πηγή φωτός για το εφέ φίλτρου. |
| [WithFePointLight](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/withfepointlight/)(*Action&lt;SVGFEPointLightElementBuilder&gt;*) | Διαμορφώνει μια σημειακή πηγή φωτός για το εφέ φίλτρου. |
| [WithFeSpotLight](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/withfespotlight/)(*Action&lt;SVGFESpotLightElementBuilder&gt;*) | Διαμορφώνει μια κωνική πηγή φωτός για το εφέ φίλτρου. |

### Δείτε επίσης

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../ifilterprimitiveinattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* class [SVGElement](../../aspose.svg/svgelement/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
