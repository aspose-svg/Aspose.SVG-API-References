---
title: "ITextureBrush Schnittstelle"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Drawing.ITextureBrush Schnittstelle. Definiert eine Pinsel‑Schnittstelle, die ein Bild verwendet, um das Innere einer Form zu füllen."
type: docs
weight: 3520
url: /de/net/aspose.svg.drawing/itexturebrush/
---
## ITextureBrush interface

Definiert ein Pinsel-Interface, das ein Bild verwendet, um das Innere einer Form zu füllen.

```csharp
public interface ITextureBrush : ITransformableBrush
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ColorMap](../../aspose.svg.drawing/itexturebrush/colormap/) { get; } | Die Anzahl der Elemente muss gerade sein. Jedes gerade Element ist die alte Farbe. Jedes ungerade Element ist die neue Farbe. |
| [Image](../../aspose.svg.drawing/itexturebrush/image/) { get; } | Liest oder setzt das vom Pinsel verwendete Bild. |
| [ImageArea](../../aspose.svg.drawing/itexturebrush/imagearea/) { get; } | Gibt den Teil des Bildes an, der vom Pinsel verwendet wird. Wenn er gleich RectangleF.Empty ist, wird das gesamte Bild verwendet. Die Koordinaten sind in Pixeln. |
| [Opacity](../../aspose.svg.drawing/itexturebrush/opacity/) { get; set; } | Erhalte den Opazitätswert in einer Farbtransformationsmatrix. |

### Siehe auch

* interface [ITransformableBrush](../itransformablebrush/)
* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
