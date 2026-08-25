---
title: "Enum PaintOrder"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Aspose.Svg.Builder.PaintOrder enum. Spécifie l'ordre dans lequel le remplissage, le trait et les marqueurs sont appliqués aux éléments SVG"
type: docs
weight: 990
url: /fr/net/aspose.svg.builder/paintorder/
---
## PaintOrder enumeration

Spécifie l'ordre dans lequel le remplissage, le contour et les marqueurs sont appliqués aux éléments SVG.

```csharp
public enum PaintOrder
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Normal | `0` | L'ordre de peinture par défaut : d'abord le remplissage, puis le trait, et enfin les marqueurs. |
| Fill | `1` | Peindre uniquement le remplissage. |
| Stroke | `2` | Peindre uniquement le trait. |
| Markers | `3` | Peindre uniquement les marqueurs. |
| FillStroke | `4` | Peindre dans l'ordre suivant : remplissage, puis trait. |
| FillMarkers | `5` | Peindre dans l'ordre suivant : remplissage, puis marqueurs. |
| StrokeFill | `6` | Peindre dans l'ordre suivant : trait, puis remplissage. |
| StrokeMarkers | `7` | Peindre dans l'ordre suivant : trait, puis marqueurs. |
| MarkersFill | `8` | Peindre dans l'ordre suivant : marqueurs, puis remplissage. |
| MarkersStroke | `9` | Peindre dans l'ordre suivant : marqueurs, puis trait. |
| FillStrokeMarkers | `10` | Peindre dans l'ordre suivant : remplissage, puis trait, et enfin les marqueurs. |
| FillMarkersStroke | `11` | Peindre dans l'ordre suivant : remplissage, puis marqueurs, et enfin le trait. |
| StrokeFillMarkers | `12` | Peindre dans l'ordre suivant : trait, puis remplissage, et enfin les marqueurs. |
| StrokeMarkersFill | `13` | Peindre dans l'ordre suivant : trait, puis marqueurs, et enfin le remplissage. |
| MarkersFillStroke | `14` | Peindre dans l'ordre suivant : marqueurs, puis remplissage, et enfin le trait. |
| MarkersStrokeFill | `15` | Peindre dans l'ordre suivant : marqueurs, puis trait, et enfin le remplissage. |

### Voir aussi

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
