---
title: "ImageDevice.ImageGraphicContext Klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Rendering.Image.ImageDeviceImageGraphicContext klasse. Bevat de huidige grafische controle‑parameters voor de ImageDevice. Deze parameters definiëren het globale kader waarbinnen de grafische operatoren worden uitgevoerd."
type: docs
weight: 4920
url: /nl/net/aspose.svg.rendering.image/imagedevice.imagegraphiccontext/
---
## ImageDevice.ImageGraphicContext class

Bevat de huidige grafische controleparameters voor de [`ImageDevice`](../imagedevice/). Deze parameters definiëren het globale kader waarbinnen de grafische operatoren worden uitgevoerd.

```csharp
public class ImageGraphicContext : GraphicContext
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [ImageGraphicContext](../../aspose.svg.rendering.image/imagedevice.imagegraphiccontext/.ctor)() | De standaardconstructor. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| virtual [CharacterSpacing](../../aspose.svg.rendering/graphiccontext/characterspacing/) { get; set; } | Stelt de tekenafstand in of haalt deze op. |
| [CurrentElement](../../aspose.svg.rendering/graphiccontext/currentelement/) { get; } | Haalt het momenteel verwerkte element op. |
| virtual [FillBrush](../../aspose.svg.rendering/graphiccontext/fillbrush/) { get; set; } | Stelt het penseelobject in dat wordt gebruikt om de binnenkanten van paden te vullen, of haalt het op. |
| virtual [Font](../../aspose.svg.rendering/graphiccontext/font/) { get; set; } | Stelt het TrueType‑lettertypeobject in dat wordt gebruikt voor het renderen van tekst, of haalt het op. |
| virtual [FontSize](../../aspose.svg.rendering/graphiccontext/fontsize/) { get; set; } | Stelt de tekstlettergrootte in of haalt deze op. |
| virtual [FontStyle](../../aspose.svg.rendering/graphiccontext/fontstyle/) { get; set; } | Stelt de tekstletterstijl in of haalt deze op. |
| virtual [LineCap](../../aspose.svg.rendering/graphiccontext/linecap/) { get; set; } | Stelt de code in die de vorm van de eindpunten specificeert voor elk geopend pad dat wordt getekend, of haalt deze op. |
| virtual [LineDashOffset](../../aspose.svg.rendering/graphiccontext/linedashoffset/) { get; set; } | Stelt de fase‑offset in van het huidige streepjes‑patroon van de lijn, of haalt deze op. |
| virtual [LineDashPattern](../../aspose.svg.rendering/graphiccontext/linedashpattern/) { get; set; } | Stelt de beschrijving in van het streepjes‑patroon dat moet worden gebruikt wanneer paden worden getekend, of haalt deze op. Kan worden ingesteld op `null` of een lege array om uitgeschakeld te zijn. |
| virtual [LineJoin](../../aspose.svg.rendering/graphiccontext/linejoin/) { get; set; } | Stelt de code in die de vorm van de verbindingen tussen verbonden segmenten van een getekend pad specificeert, of haalt deze op. |
| virtual [LineWidth](../../aspose.svg.rendering/graphiccontext/linewidth/) { get; set; } | Stelt de dikte van paden in die getekend moeten worden, of haalt deze op. |
| virtual [MiterLimit](../../aspose.svg.rendering/graphiccontext/miterlimit/) { get; set; } | Stelt de maximale lengte van afgeschuinde lijnverbindingen voor getekende paden in, of haalt deze op. Deze parameter beperkt de lengte van \"spikes\" die ontstaan wanneer lijnsegmenten bij scherpe hoeken samenkomen. |
| virtual [StrokeBrush](../../aspose.svg.rendering/graphiccontext/strokebrush/) { get; set; } | Stelt het penseelobject in dat wordt gebruikt voor getekende paden, of haalt dit op. |
| virtual [TextInfo](../../aspose.svg.rendering/graphiccontext/textinfo/) { get; } | Haalt een [`TextInfo`](../../aspose.svg.rendering/textinfo/) object op dat informatie bevat over gerenderde tekst. |
| virtual [TransformationMatrix](../../aspose.svg.rendering/graphiccontext/transformationmatrix/) { get; set; } | Stelt de transformatie‑matrix in, of haalt deze op. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| virtual [Clone](../../aspose.svg.rendering/graphiccontext/clone/)() | Maakt een nieuw exemplaar van de GraphicContext‑klasse aan met dezelfde eigenschapswaarden als een bestaand exemplaar. |
| virtual [Transform](../../aspose.svg.rendering/graphiccontext/transform/)(*[IMatrix](../../aspose.svg.drawing/imatrix/)*) | Wijzig de huidige transformatie‑matrix door de opgegeven matrix te vermenigvuldigen. |

### Zie ook

* class [GraphicContext](../../aspose.svg.rendering/graphiccontext/)
* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Svg.Rendering.Image](../../aspose.svg.rendering.image/)
* assembly [Aspose.SVG](../../)
