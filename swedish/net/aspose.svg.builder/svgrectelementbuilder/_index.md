---
title: "SVGRectElementBuilder klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Builder.SVGRectElementBuilder klass. Byggklass för att konstruera ett SVG rect-element. Rect-elementet används för att skapa rektanglar inom SVG-grafik. Denna klass tillhandahåller metoder för att ställa in olika attribut som är specifika för rect-elementet, inklusive hörnradier och dimensioner."
type: docs
weight: 1580
url: /sv/net/aspose.svg.builder/svgrectelementbuilder/
---
## SVGRectElementBuilder class

Builder-klass för att konstruera ett SVG 'rect'-element. 'Rect'-elementet används för att skapa rektanglar inom SVG-grafik. Denna klass tillhandahåller metoder för att ange olika attribut som är specifika för 'rect'-elementet, inklusive hörnradier och dimensioner.

```csharp
public class SVGRectElementBuilder : SVGElementBuilder<SVGRectElement>, IAnimationElementBuilder, 
    IDescriptiveElementBuilder, IPaintServerElementBuilder, IRectAttributeSetter, 
    IShapeAttributeSetter, IShapeContentElementBuilder
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SVGRectElementBuilder](svgrectelementbuilder/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGRectElement](../../aspose.svg/svgrectelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Rx](../../aspose.svg.builder/svgrectelementbuilder/rx/)(*double, [LengthType](../lengthtype/)*) | Ställer in attributet 'rx' för SVG 'rect'-elementet och specificerar den horisontella radien för rektangelns rundade hörn. |
| [Ry](../../aspose.svg.builder/svgrectelementbuilder/ry/)(*double, [LengthType](../lengthtype/)*) | Ställer in attributet 'ry' för SVG 'rect'-elementet och specificerar den vertikala radien för rektangelns rundade hörn. |

### Se även

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGRectElement](../../aspose.svg/svgrectelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IPaintServerElementBuilder](../ipaintserverelementbuilder/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* interface [IShapeAttributeSetter](../ishapeattributesetter/)
* interface [IShapeContentElementBuilder](../ishapecontentelementbuilder/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
