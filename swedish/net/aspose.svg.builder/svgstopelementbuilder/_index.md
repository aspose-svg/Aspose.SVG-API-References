---
title: "SVGStopElementBuilder Class"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Builder.SVGStopElementBuilder klass. Byggklass för att konstruera ett SVG‑stop‑element. Stop‑elementet används i en gradientdefinition, antingen linjär eller radiell, för att definiera färgstopp. Denna klass tillhandahåller metoder för att ställa in olika attribut som är specifika för stop‑elementet, såsom offset och färg."
type: docs
weight: 1620
url: /sv/net/aspose.svg.builder/svgstopelementbuilder/
---
## SVGStopElementBuilder class

Builder-klass för att konstruera ett SVG 'stop'-element. 'Stop'-elementet används inom en gradientdefinition (antingen linjär eller radiell) för att definiera färgstopp. Denna klass tillhandahåller metoder för att ange olika attribut som är specifika för 'stop'-elementet, såsom offset och färg.

```csharp
public class SVGStopElementBuilder : SVGElementBuilder<SVGStopElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDocumentElementEventAttributeSetter, 
    IGlobalEventAttributeSetter, IPresentationAttributeSetter
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SVGStopElementBuilder](svgstopelementbuilder/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgstopelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | Lägger till en skriptkonfiguration i SVG‑elementet 'stop'. |
| [AddStyle](../../aspose.svg.builder/svgstopelementbuilder/addstyle/)(*Action&lt;SVGStyleElementBuilder&gt;*) | Lägger till en stilkonfiguration i SVG‑elementet 'stop'. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGStopElement](../../aspose.svg/svgstopelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Offset](../../aspose.svg.builder/svgstopelementbuilder/offset/)(*double, [StopUnitType](../stopunittype/)*) | Ställer in attributet 'offset' för SVG‑elementet 'stop' och specificerar positionen för färgstoppet inom gradienten. |

### Se även

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGStopElement](../../aspose.svg/svgstopelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
