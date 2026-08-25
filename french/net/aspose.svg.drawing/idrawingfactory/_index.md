---
title: "IDrawingFactory Interface"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Aspose.Svg.Drawing.IDrawingFactory interface. Représente une usine pour créer des objets liés au dessin"
type: docs
weight: 3460
url: /fr/net/aspose.svg.drawing/idrawingfactory/
---
## IDrawingFactory interface

Représente une usine pour créer des objets liés au dessin.

```csharp
public interface IDrawingFactory : IDisposable
```

## Méthodes

| Nom | Description |
| --- | --- |
| [CreateInterpolationColor](../../aspose.svg.drawing/idrawingfactory/createinterpolationcolor/)(*Color, float*) | Crée une couleur d'interpolation avec la couleur et la position spécifiées. |
| [CreateLinearGradientBrush](../../aspose.svg.drawing/idrawingfactory/createlineargradientbrush/)(*RectangleF, IInterpolationColor[]*) | Crée un pinceau de dégradé linéaire avec les paramètres spécifiés. |
| [CreateMatrix](../../aspose.svg.drawing/idrawingfactory/creatematrix/#creatematrix)() | Crée une nouvelle matrice d'identité. |
| [CreateMatrix](../../aspose.svg.drawing/idrawingfactory/creatematrix/#creatematrix_1)(*[IMatrix](../imatrix/)*) | Crée une nouvelle matrice avec le même contenu que la matrice spécifiée. |
| [CreateMatrix](../../aspose.svg.drawing/idrawingfactory/creatematrix/#creatematrix_2)(*float, float, float, float, float, float*) | Crée une nouvelle matrice avec les éléments spécifiés. |
| [CreateSolidBrush](../../aspose.svg.drawing/idrawingfactory/createsolidbrush/)(*Color*) | Crée un pinceau plein avec la couleur spécifiée. |
| [CreateTextureBrush](../../aspose.svg.drawing/idrawingfactory/createtexturebrush/)(*byte[]*) | Crée un pinceau de texture avec les paramètres spécifiés. |

### Voir aussi

* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
