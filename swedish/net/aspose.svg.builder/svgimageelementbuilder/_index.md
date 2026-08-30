---
title: "SVGImageElementBuilder-klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Builder.SVGImageElementBuilder-klass. Byggklass för att konstruera ett SVG-bildelement. Detta element används för att bädda in bilder i SVG-grafik. Den tillhandahåller metoder för att ställa in olika attribut som är specifika för bildelementet och för att lägga till ytterligare konfigurationer som beskärningsvägar, masker, stilar och skript."
type: docs
weight: 1470
url: /sv/net/aspose.svg.builder/svgimageelementbuilder/
---
## SVGImageElementBuilder class

Builder-klass för att konstruera ett SVG 'image'-element. Detta element används för att bädda in bilder i SVG-grafik. Det tillhandahåller metoder för att ställa in olika attribut specifika för 'image'-elementet samt för att lägga till ytterligare konfigurationer som klippvägar, masker, stilar och skript.

```csharp
public class SVGImageElementBuilder : SVGElementBuilder<SVGImageElement>, IAnimationElementBuilder, 
    ICompositeAttributeSetter, IDescriptiveElementBuilder, IPreserveAspectRatioAttributeSetter, 
    IRectAttributeSetter
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SVGImageElementBuilder](svgimageelementbuilder/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddClipPath](../../aspose.svg.builder/svgimageelementbuilder/addclippath/)(*Action&lt;SVGClipPathElementBuilder&gt;*) | Lägger till en beskärningsvägskonfiguration till SVG 'image'-elementet. |
| [AddMask](../../aspose.svg.builder/svgimageelementbuilder/addmask/)(*Action&lt;SVGMaskElementBuilder&gt;*) | Lägger till en maskkonfiguration till SVG 'image'-elementet. |
| [AddScript](../../aspose.svg.builder/svgimageelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | Lägger till en skriptkonfiguration till SVG 'image'-elementet. |
| [AddStyle](../../aspose.svg.builder/svgimageelementbuilder/addstyle/)(*Action&lt;SVGStyleElementBuilder&gt;*) | Lägger till en stilkonfiguration till SVG 'image'-elementet. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGImageElement](../../aspose.svg/svgimageelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Href](../../aspose.svg.builder/svgimageelementbuilder/href/)(*string*) | Ställer in 'href'-attributet för SVG 'image'-elementet och specificerar URL:en för bilden som ska bäddas in. |
| [HrefBase64FromBytes](../../aspose.svg.builder/svgimageelementbuilder/hrefbase64frombytes/)(*byte[], string*) | Ställer in 'href'-attributet för SVG 'image'-elementet med base64-kodade byte av en bild. |
| [HrefBase64FromFile](../../aspose.svg.builder/svgimageelementbuilder/hrefbase64fromfile/#hrefbase64fromfile)(*string*) | Ställer in 'href'-attributet för SVG 'image'-elementet med en base64-kodad bildfil. |
| [HrefBase64FromFile](../../aspose.svg.builder/svgimageelementbuilder/hrefbase64fromfile/#hrefbase64fromfile_1)(*string, string*) | Ställer in 'href'-attributet för SVG 'image'-elementet med en base64-kodad bildfil med en specificerad MIME-typ. |

### Se även

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGImageElement](../../aspose.svg/svgimageelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IPreserveAspectRatioAttributeSetter](../ipreserveaspectratioattributesetter/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
