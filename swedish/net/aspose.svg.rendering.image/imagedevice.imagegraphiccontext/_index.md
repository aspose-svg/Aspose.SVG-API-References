---
title: "ImageDevice.ImageGraphicContext-klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Rendering.Image.ImageDeviceImageGraphicContext-klass. Innehåller aktuella grafikstyrningsparametrar för ImageDevice. Dessa parametrar definierar det globala ramverket inom vilket grafikoperatorerna körs."
type: docs
weight: 4920
url: /sv/net/aspose.svg.rendering.image/imagedevice.imagegraphiccontext/
---
## ImageDevice.ImageGraphicContext class

Innehåller aktuella grafikstyrningsparametrar för [`ImageDevice`](../imagedevice/). Dessa parametrar definierar det globala ramverket inom vilket grafikoperatorerna körs.

```csharp
public class ImageGraphicContext : GraphicContext
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ImageGraphicContext](../../aspose.svg.rendering.image/imagedevice.imagegraphiccontext/.ctor)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| virtual [CharacterSpacing](../../aspose.svg.rendering/graphiccontext/characterspacing/) { get; set; } | Ställer in eller hämtar teckenavstånd. |
| [CurrentElement](../../aspose.svg.rendering/graphiccontext/currentelement/) { get; } | Hämtar aktuellt bearbetat element. |
| virtual [FillBrush](../../aspose.svg.rendering/graphiccontext/fillbrush/) { get; set; } | Ställer in eller hämtar penselobjektet som används för att fylla insidan av banor. |
| virtual [Font](../../aspose.svg.rendering/graphiccontext/font/) { get; set; } | Ställer in eller hämtar TrueType‑teckensnittobjektet som används för att rendera text. |
| virtual [FontSize](../../aspose.svg.rendering/graphiccontext/fontsize/) { get; set; } | Ställer in eller hämtar textens teckenstorlek. |
| virtual [FontStyle](../../aspose.svg.rendering/graphiccontext/fontstyle/) { get; set; } | Ställer in eller hämtar textens teckenstil. |
| virtual [LineCap](../../aspose.svg.rendering/graphiccontext/linecap/) { get; set; } | Ställer in eller hämtar koden som specificerar formen på ändpunkterna för någon öppen bana som strokas. |
| virtual [LineDashOffset](../../aspose.svg.rendering/graphiccontext/linedashoffset/) { get; set; } | Ställer in eller hämtar fasförskjutningen för det aktuella streckmönstret. |
| virtual [LineDashPattern](../../aspose.svg.rendering/graphiccontext/linedashpattern/) { get; set; } | Ställer in eller hämtar beskrivningen av streckmönstret som ska användas när banor strokas. Kan sättas till null eller en tom array för att inaktiveras. |
| virtual [LineJoin](../../aspose.svg.rendering/graphiccontext/linejoin/) { get; set; } | Ställer in eller hämtar koden som specificerar formen på fogarna mellan anslutna segment av en strokad bana. |
| virtual [LineWidth](../../aspose.svg.rendering/graphiccontext/linewidth/) { get; set; } | Ställer in eller hämtar tjockleken på banor som ska strokas. |
| virtual [MiterLimit](../../aspose.svg.rendering/graphiccontext/miterlimit/) { get; set; } | Ställer in eller hämtar den maximala längden på snedställda linjeskarvar för strokade banor. Denna parameter begränsar längden på \"spikes\" som bildas när linjesegment möts i skarpa vinklar. |
| virtual [StrokeBrush](../../aspose.svg.rendering/graphiccontext/strokebrush/) { get; set; } | Ställer in eller hämtar penselobjektet som används för strokade banor. |
| virtual [TextInfo](../../aspose.svg.rendering/graphiccontext/textinfo/) { get; } | Hämtar ett [`TextInfo`](../../aspose.svg.rendering/textinfo/)‑objekt som innehåller information om renderad text. |
| virtual [TransformationMatrix](../../aspose.svg.rendering/graphiccontext/transformationmatrix/) { get; set; } | Ställer in eller hämtar transformationsmatris. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| virtual [Clone](../../aspose.svg.rendering/graphiccontext/clone/)() | Skapar en ny instans av en GraphicContext-klass med samma egenskapsvärden som en befintlig instans. |
| virtual [Transform](../../aspose.svg.rendering/graphiccontext/transform/)(*[IMatrix](../../aspose.svg.drawing/imatrix/)*) | Modifierar den aktuella transformationsmatrisen genom att multiplicera med den angivna matrisen. |

### Se även

* class [GraphicContext](../../aspose.svg.rendering/graphiccontext/)
* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Svg.Rendering.Image](../../aspose.svg.rendering.image/)
* assembly [Aspose.SVG](../../)
