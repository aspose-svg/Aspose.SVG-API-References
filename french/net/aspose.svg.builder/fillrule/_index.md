---
title: "Enum FillRule"
second_title: "Aspose.SVG pour .NET Référence de l'API"
description: "Aspose.Svg.Builder.FillRule enum. Spécifie la règle permettant de déterminer quelles parties d'une forme sont à l'intérieur ou à l'extérieur dans les graphiques SVG."
type: docs
weight: 270
url: /fr/net/aspose.svg.builder/fillrule/
---
## FillRule enumeration

Spécifie la règle permettant de déterminer quelles parties d’une forme sont à l’intérieur ou à l’extérieur dans les graphiques SVG.

```csharp
public enum FillRule
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Nonzero | `0` | La règle de winding non nulle : Détermine le « intérieur » d'un point dans la forme en traçant un rayon depuis ce point vers l'infini dans n'importe quelle direction et en comptant le nombre de segments de chemin de la forme donnée que le rayon traverse. Si ce nombre est impair, le point est à l'intérieur ; s'il est pair, le point est à l'extérieur. |
| Evenodd | `1` | La règle de winding pair‑impair : Détermine le « intérieur » d'un point dans la forme en traçant un rayon depuis ce point vers l'infini dans n'importe quelle direction et en comptant le nombre de segments de chemin de la forme donnée que le rayon traverse. Si ce nombre est pair, le point est à l'extérieur ; s'il est impair, le point est à l'intérieur. |

### Voir aussi

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
