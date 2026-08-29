---
title: "IDrawingFactory interface"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Drawing.IDrawingFactory interface. Vertegenwoordigt een fabriek voor het maken van tekengerelateerde objecten"
type: docs
weight: 3460
url: /nl/net/aspose.svg.drawing/idrawingfactory/
---
## IDrawingFactory interface

Stelt een fabriek voor het maken van teken-gerelateerde objecten voor.

```csharp
public interface IDrawingFactory : IDisposable
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [CreateInterpolationColor](../../aspose.svg.drawing/idrawingfactory/createinterpolationcolor/)(*Color, float*) | Maakt een interpolatiekleur met de opgegeven kleur en positie. |
| [CreateLinearGradientBrush](../../aspose.svg.drawing/idrawingfactory/createlineargradientbrush/)(*RectangleF, IInterpolationColor[]*) | Maakt een lineaire gradientkwast met de opgegeven parameters. |
| [CreateMatrix](../../aspose.svg.drawing/idrawingfactory/creatematrix/#creatematrix)() | Maakt een nieuwe identiteitsmatrix. |
| [CreateMatrix](../../aspose.svg.drawing/idrawingfactory/creatematrix/#creatematrix_1)(*[IMatrix](../imatrix/)*) | Maakt een nieuwe matrix met dezelfde inhoud als de opgegeven matrix. |
| [CreateMatrix](../../aspose.svg.drawing/idrawingfactory/creatematrix/#creatematrix_2)(*float, float, float, float, float, float*) | Maakt een nieuwe matrix met de opgegeven elementen. |
| [CreateSolidBrush](../../aspose.svg.drawing/idrawingfactory/createsolidbrush/)(*Color*) | Maakt een effen kwast met de opgegeven kleur. |
| [CreateTextureBrush](../../aspose.svg.drawing/idrawingfactory/createtexturebrush/)(*byte[]*) | Maakt een textuurkwast met de opgegeven parameters. |

### Zie ook

* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
