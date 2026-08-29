---
title: "ITextureBrush Interface"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Drawing.ITextureBrush interface. Definieert een penseelinterface die een afbeelding gebruikt om het interieur van een vorm te vullen."
type: docs
weight: 3520
url: /nl/net/aspose.svg.drawing/itexturebrush/
---
## ITextureBrush interface

Definieert een penseelinterface die een afbeelding gebruikt om de binnenkant van een vorm te vullen.

```csharp
public interface ITextureBrush : ITransformableBrush
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [ColorMap](../../aspose.svg.drawing/itexturebrush/colormap/) { get; } | Het aantal elementen moet even zijn. Elk even element is de oude kleur. Elk oneven element is de nieuwe kleur. |
| [Image](../../aspose.svg.drawing/itexturebrush/image/) { get; } | Haalt op of stelt de afbeelding in die door de penseel wordt gebruikt. |
| [ImageArea](../../aspose.svg.drawing/itexturebrush/imagearea/) { get; } | Specificeert het gedeelte van de afbeelding dat door de penseel wordt gebruikt. Als het gelijk is aan RectangleF.Empty, wordt de volledige afbeelding gebruikt. Coördinaten zijn in pixels. |
| [Opacity](../../aspose.svg.drawing/itexturebrush/opacity/) { get; set; } | Haal de opaciteitswaarde op in een kleurtransformatiesmatrix. |

### Zie ook

* interface [ITransformableBrush](../itransformablebrush/)
* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
