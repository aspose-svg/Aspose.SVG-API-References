---
title: "IDrawingFactory Interfaccia"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Aspose.Svg.Drawing.IDrawingFactory interface. Rappresenta una fabbrica per la creazione di oggetti relativi al disegno"
type: docs
weight: 3460
url: /it/net/aspose.svg.drawing/idrawingfactory/
---
## IDrawingFactory interface

Rappresenta una fabbrica per la creazione di oggetti relativi al disegno.

```csharp
public interface IDrawingFactory : IDisposable
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [CreateInterpolationColor](../../aspose.svg.drawing/idrawingfactory/createinterpolationcolor/)(*Color, float*) | Crea un colore di interpolazione con il colore e la posizione specificati. |
| [CreateLinearGradientBrush](../../aspose.svg.drawing/idrawingfactory/createlineargradientbrush/)(*RectangleF, IInterpolationColor[]*) | Crea un pennello a gradiente lineare con i parametri specificati. |
| [CreateMatrix](../../aspose.svg.drawing/idrawingfactory/creatematrix/#creatematrix)() | Crea una nuova matrice identità. |
| [CreateMatrix](../../aspose.svg.drawing/idrawingfactory/creatematrix/#creatematrix_1)(*[IMatrix](../imatrix/)*) | Crea una nuova matrice con gli stessi contenuti della matrice specificata. |
| [CreateMatrix](../../aspose.svg.drawing/idrawingfactory/creatematrix/#creatematrix_2)(*float, float, float, float, float, float*) | Crea una nuova matrice con gli elementi specificati. |
| [CreateSolidBrush](../../aspose.svg.drawing/idrawingfactory/createsolidbrush/)(*Color*) | Crea un pennello solido con il colore specificato. |
| [CreateTextureBrush](../../aspose.svg.drawing/idrawingfactory/createtexturebrush/)(*byte[]*) | Crea un pennello texture con i parametri specificati. |

### Vedi anche

* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
