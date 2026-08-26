---
title: "Κλάση SVGImageElementBuilder"
second_title: "Aspose.SVG για .NET API Αναφορά"
description: "Aspose.Svg.Builder.SVGImageElementBuilder class. Κλάση δημιουργού για την κατασκευή ενός στοιχείου εικόνας SVG. Αυτό το στοιχείο χρησιμοποιείται για την ενσωμάτωση εικόνων μέσα σε γραφικά SVG. Παρέχει μεθόδους για τον ορισμό διαφόρων χαρακτηριστικών ειδικών για το στοιχείο εικόνας και για την προσθήκη επιπλέον ρυθμίσεων όπως διαδρομές αποκοπής, μάσκες, στυλ και σενάρια."
type: docs
weight: 1470
url: /el/net/aspose.svg.builder/svgimageelementbuilder/
---
## SVGImageElementBuilder class

Κλάση Builder για την κατασκευή ενός στοιχείου SVG 'image'. Αυτό το στοιχείο χρησιμοποιείται για την ενσωμάτωση εικόνων μέσα σε γραφικά SVG. Παρέχει μεθόδους για τον ορισμό διαφόρων χαρακτηριστικών ειδικών για το στοιχείο 'image' και για την προσθήκη πρόσθετων ρυθμίσεων όπως διαδρομές αποκοπής, μάσκες, στυλ και σενάρια.

```csharp
public class SVGImageElementBuilder : SVGElementBuilder<SVGImageElement>, IAnimationElementBuilder, 
    ICompositeAttributeSetter, IDescriptiveElementBuilder, IPreserveAspectRatioAttributeSetter, 
    IRectAttributeSetter
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [SVGImageElementBuilder](svgimageelementbuilder/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddClipPath](../../aspose.svg.builder/svgimageelementbuilder/addclippath/)(*Action&lt;SVGClipPathElementBuilder&gt;*) | Προσθέτει μια ρύθμιση διαδρομής αποκοπής στο στοιχείο SVG 'image'. |
| [AddMask](../../aspose.svg.builder/svgimageelementbuilder/addmask/)(*Action&lt;SVGMaskElementBuilder&gt;*) | Προσθέτει μια ρύθμιση μάσκας στο στοιχείο SVG 'image'. |
| [AddScript](../../aspose.svg.builder/svgimageelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | Προσθέτει μια ρύθμιση σεναρίου στο στοιχείο SVG 'image'. |
| [AddStyle](../../aspose.svg.builder/svgimageelementbuilder/addstyle/)(*Action&lt;SVGStyleElementBuilder&gt;*) | Προσθέτει μια ρύθμιση στυλ στο στοιχείο SVG 'image'. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGImageElement](../../aspose.svg/svgimageelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Href](../../aspose.svg.builder/svgimageelementbuilder/href/)(*string*) | Ορίζει το χαρακτηριστικό 'href' του στοιχείου SVG 'image', καθορίζοντας το URL της εικόνας που θα ενσωματωθεί. |
| [HrefBase64FromBytes](../../aspose.svg.builder/svgimageelementbuilder/hrefbase64frombytes/)(*byte[], string*) | Ορίζει το χαρακτηριστικό 'href' του στοιχείου SVG 'image' χρησιμοποιώντας κωδικοποιημένα σε base64 bytes μιας εικόνας. |
| [HrefBase64FromFile](../../aspose.svg.builder/svgimageelementbuilder/hrefbase64fromfile/#hrefbase64fromfile)(*string*) | Ορίζει το χαρακτηριστικό 'href' του στοιχείου SVG 'image' χρησιμοποιώντας ένα αρχείο εικόνας κωδικοποιημένο σε base64. |
| [HrefBase64FromFile](../../aspose.svg.builder/svgimageelementbuilder/hrefbase64fromfile/#hrefbase64fromfile_1)(*string, string*) | Ορίζει το χαρακτηριστικό 'href' του στοιχείου SVG 'image' χρησιμοποιώντας ένα αρχείο εικόνας κωδικοποιημένο σε base64 με καθορισμένο τύπο MIME. |

### Δείτε επίσης

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGImageElement](../../aspose.svg/svgimageelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IPreserveAspectRatioAttributeSetter](../ipreserveaspectratioattributesetter/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
