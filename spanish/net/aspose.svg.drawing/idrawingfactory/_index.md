---
title: "Interfaz IDrawingFactory"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Interfaz Aspose.Svg.Drawing.IDrawingFactory. Representa una fábrica para crear objetos relacionados con el dibujo"
type: docs
weight: 3460
url: /es/net/aspose.svg.drawing/idrawingfactory/
---
## IDrawingFactory interface

Representa una fábrica para crear objetos relacionados con el dibujo.

```csharp
public interface IDrawingFactory : IDisposable
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CreateInterpolationColor](../../aspose.svg.drawing/idrawingfactory/createinterpolationcolor/)(*Color, float*) | Crea un color de interpolación con el color y la posición especificados. |
| [CreateLinearGradientBrush](../../aspose.svg.drawing/idrawingfactory/createlineargradientbrush/)(*RectangleF, IInterpolationColor[]*) | Crea un pincel de degradado lineal con los parámetros especificados. |
| [CreateMatrix](../../aspose.svg.drawing/idrawingfactory/creatematrix/#creatematrix)() | Crea una nueva matriz de identidad. |
| [CreateMatrix](../../aspose.svg.drawing/idrawingfactory/creatematrix/#creatematrix_1)(*[IMatrix](../imatrix/)*) | Crea una nueva matriz con el mismo contenido que la matriz especificada. |
| [CreateMatrix](../../aspose.svg.drawing/idrawingfactory/creatematrix/#creatematrix_2)(*float, float, float, float, float, float*) | Crea una nueva matriz con los elementos especificados. |
| [CreateSolidBrush](../../aspose.svg.drawing/idrawingfactory/createsolidbrush/)(*Color*) | Crea un pincel sólido con el color especificado. |
| [CreateTextureBrush](../../aspose.svg.drawing/idrawingfactory/createtexturebrush/)(*byte[]*) | Crea un pincel de textura con los parámetros especificados. |

### Ver también

* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
