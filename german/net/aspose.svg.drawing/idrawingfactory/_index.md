---
title: "IDrawingFactory Schnittstelle"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Drawing.IDrawingFactory Schnittstelle. Stellt eine Fabrik zum Erstellen von zeichnungsbezogenen Objekten dar."
type: docs
weight: 3460
url: /de/net/aspose.svg.drawing/idrawingfactory/
---
## IDrawingFactory interface

Stellt eine Fabrik zur Erstellung von zeichnungsbezogenen Objekten dar.

```csharp
public interface IDrawingFactory : IDisposable
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CreateInterpolationColor](../../aspose.svg.drawing/idrawingfactory/createinterpolationcolor/)(*Color, float*) | Erstellt eine Interpolationsfarbe mit der angegebenen Farbe und Position. |
| [CreateLinearGradientBrush](../../aspose.svg.drawing/idrawingfactory/createlineargradientbrush/)(*RectangleF, IInterpolationColor[]*) | Erstellt einen linearen Farbverlauf-Pinsel mit den angegebenen Parametern. |
| [CreateMatrix](../../aspose.svg.drawing/idrawingfactory/creatematrix/#creatematrix)() | Erstellt eine neue Einheitsmatrix. |
| [CreateMatrix](../../aspose.svg.drawing/idrawingfactory/creatematrix/#creatematrix_1)(*[IMatrix](../imatrix/)*) | Erstellt eine neue Matrix mit dem gleichen Inhalt wie die angegebene Matrix. |
| [CreateMatrix](../../aspose.svg.drawing/idrawingfactory/creatematrix/#creatematrix_2)(*float, float, float, float, float, float*) | Erstellt eine neue Matrix mit den angegebenen Elementen. |
| [CreateSolidBrush](../../aspose.svg.drawing/idrawingfactory/createsolidbrush/)(*Color*) | Erstellt einen Vollpinsel mit der angegebenen Farbe. |
| [CreateTextureBrush](../../aspose.svg.drawing/idrawingfactory/createtexturebrush/)(*byte[]*) | Erstellt einen Textur-Pinsel mit den angegebenen Parametern. |

### Siehe auch

* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
