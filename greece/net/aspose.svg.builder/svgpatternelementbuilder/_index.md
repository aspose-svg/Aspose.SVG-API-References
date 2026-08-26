---
title: "Κλάση SVGPatternElementBuilder"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Aspose.Svg.Builder.SVGPatternElementBuilder class. Κλάση δημιουργού για την κατασκευή ενός στοιχείου προτύπου SVG που χρησιμοποιείται για τον ορισμό ενός προτύπου που θα χρησιμοποιηθεί για το γέμισμα γραφικών στοιχείων εντός SVG. Αυτή η κλάση παρέχει μεθόδους για τον ορισμό διαφόρων χαρακτηριστικών ειδικών για το στοιχείο προτύπου και για τη δημιουργία του περιεχομένου του."
type: docs
weight: 1540
url: /el/net/aspose.svg.builder/svgpatternelementbuilder/
---
## SVGPatternElementBuilder class

Κλάση Builder για την κατασκευή ενός στοιχείου SVG 'pattern', που χρησιμοποιείται για τον ορισμό μοτίβου που θα χρησιμοποιηθεί για το γέμισμα γραφικών στοιχείων μέσα στο SVG. Αυτή η κλάση παρέχει μεθόδους για τον ορισμό διαφόρων χαρακτηριστικών ειδικών για το στοιχείο 'pattern' και για τη δημιουργία του περιεχομένου του.

```csharp
public class SVGPatternElementBuilder : SVGElementBuilder<SVGPatternElement>, 
    ICompositeElementBuilder, ICoreAttributeSetter, IGlobalEventAttributeSetter, 
    IPresentationAttributeSetter, IPreserveAspectRatioAttributeSetter, IRectAttributeSetter, 
    IViewBoxAttributeSetter
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [SVGPatternElementBuilder](svgpatternelementbuilder/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGPatternElement](../../aspose.svg/svgpatternelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Href](../../aspose.svg.builder/svgpatternelementbuilder/href/)(*string*) | Ορίζει το χαρακτηριστικό 'href' του στοιχείου SVG 'pattern', καθορίζοντας μια αναφορά σε άλλο πρότυπο από το οποίο αυτό το πρότυπο κληρονομεί χαρακτηριστικά. |
| [PatternContentUnits](../../aspose.svg.builder/svgpatternelementbuilder/patterncontentunits/)(*[CoordinateUnits](../coordinateunits/)*) | Ορίζει το χαρακτηριστικό 'patternContentUnits' του στοιχείου SVG 'pattern', καθορίζοντας το σύστημα συντεταγμένων για το περιεχόμενο του προτύπου. |
| [PatternTransform](../../aspose.svg.builder/svgpatternelementbuilder/patterntransform/)(*Func&lt;TransformBuilder, TransformBuilder&gt;*) | Ορίζει το χαρακτηριστικό 'patternTransform' του στοιχείου SVG 'pattern', εφαρμόζοντας μια μετασχηματισμό στο πρότυπο. |
| [PatternUnits](../../aspose.svg.builder/svgpatternelementbuilder/patternunits/)(*[CoordinateUnits](../coordinateunits/)*) | Ορίζει το χαρακτηριστικό 'patternUnits' του στοιχείου SVG 'pattern', καθορίζοντας το σύστημα συντεταγμένων για τις τιμές x, y, πλάτος και ύψος του προτύπου. |

### Δείτε επίσης

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGPatternElement](../../aspose.svg/svgpatternelement/)
* interface [ICompositeElementBuilder](../icompositeelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* interface [IPreserveAspectRatioAttributeSetter](../ipreserveaspectratioattributesetter/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* interface [IViewBoxAttributeSetter](../iviewboxattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
