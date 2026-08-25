---
title: "Enum BlendMode"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Enum Aspose.Svg.Builder.BlendMode. Spécifie les modes de fusion disponibles pour combiner des images ou des éléments dans SVG"
type: docs
weight: 80
url: /fr/net/aspose.svg.builder/blendmode/
---
## BlendMode enumeration

Spécifie les modes de fusion disponibles pour combiner des images ou des éléments dans SVG.

```csharp
public enum BlendMode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Normal | `0` | Affiche l'image source telle quelle, sans aucune fusion. |
| Multiply | `1` | Multiplie les couleurs de l'image source et de l'arrière-plan. Le résultat est une image plus sombre. |
| Screen | `2` | Rend les parties sombres de l'image source plus claires et laisse les parties claires inchangées. |
| Overlay | `3` | Combine les modes de fusion Multiply et Screen pour améliorer le contraste. |
| Darken | `4` | Assombrit l'arrière-plan en fonction des couleurs de l'image source. |
| Lighten | `5` | Éclaircit l'arrière-plan en fonction des couleurs de l'image source. |
| ColorDodge | `6` | Éclaircit l'arrière-plan pour refléter l'image source. |
| ColorBurn | `7` | Assombrit l'arrière-plan pour refléter l'image source. |
| HardLight | `8` | Crée un effet de lumière dure basé sur la luminosité de l'image source. |
| SoftLight | `9` | Crée un effet de lumière douce basé sur la luminosité de l'image source. |
| Difference | `10` | Met en évidence les différences entre l'image source et l'arrière-plan. |
| Exclusion | `11` | Crée un effet similaire à Difference, mais avec un contraste plus faible. |
| Hue | `12` | Utilise la teinte de l'image source combinée à la luminance et à la saturation de l'arrière-plan. |
| Saturation | `13` | Utilise la saturation de l'image source combinée à la teinte et à la luminance de l'arrière-plan. |
| Color | `14` | Utilise la teinte et la saturation de l'image source combinées à la luminance de l'arrière-plan. |
| Luminosity | `15` | Utilise la luminance de l'image source combinée à la teinte et à la saturation de l'arrière-plan. |

## Remarques

Les modes de fusion dans SVG sont utilisés pour déterminer comment deux calques sont mélangés entre eux. Cette énumération offre une variété d'options qui contrôlent la façon dont les couleurs des calques fusionnés se combinent et produisent différents effets visuels.

### Voir aussi

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
