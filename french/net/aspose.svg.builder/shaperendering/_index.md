---
title: "Enum ShapeRendering"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Aspose.Svg.Builder.ShapeRendering enum. Spécifie le mode de rendu des formes pour les éléments SVG"
type: docs
weight: 1720
url: /fr/net/aspose.svg.builder/shaperendering/
---
## ShapeRendering enumeration

Spécifie le mode de rendu des formes pour les éléments SVG.

```csharp
public enum ShapeRendering
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Auto | `0` | Le navigateur fait des compromis entre la vitesse, la fluidité et la précision géométrique lors du rendu des formes. |
| OptimizeSpeed | `1` | Le navigateur privilégie la vitesse de rendu au détriment de la précision géométrique et de la fluidité. Ce mode peut entraîner un rendu plus rapide mais des formes moins précises. |
| CrispEdges | `2` | Le navigateur tente de préserver les arêtes et les coins nets. Ce mode est utile pour le rendu de graphiques avec des lignes et des bords droits. |
| GeometricPrecision | `3` | Le navigateur privilégie la précision géométrique lors du rendu au détriment de la vitesse. Ce mode convient aux rendus de haute qualité où la géométrie précise est importante. |

### Voir aussi

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
