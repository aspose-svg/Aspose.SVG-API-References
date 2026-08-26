---
title: "ISVGAnimatedPathData Schnittstelle"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Paths.ISVGAnimatedPathData Schnittstelle. Die SVGAnimatedPathData Schnittstelle unterstützt Elemente, die ein d‑Attribut besitzen, das SVG‑Pfaddaten enthält, und ermöglicht die Animation dieses Attributs."
type: docs
weight: 4550
url: /de/net/aspose.svg.paths/isvganimatedpathdata/
---
## ISVGAnimatedPathData interface

Das SVGAnimatedPathData-Interface unterstützt Elemente, die ein ‘d’-Attribut besitzen, das SVG-Pfaddaten enthält, und unterstützt die Möglichkeit, dieses Attribut zu animieren.

```csharp
public interface ISVGAnimatedPathData
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AnimatedPathSegList](../../aspose.svg.paths/isvganimatedpathdata/animatedpathseglist/) { get; } | Bietet Zugriff auf die aktuellen animierten Inhalte des ‘d’-Attributs in einer Form, die eins‑zu‑eins mit der SVG‑Syntax übereinstimmt. Wenn das angegebene Attribut oder die Eigenschaft animiert wird, enthält es den aktuellen animierten Wert des Attributs oder der Eigenschaft, und sowohl das Objekt selbst als auch seine Inhalte sind schreibgeschützt. Wenn das angegebene Attribut oder die Eigenschaft derzeit nicht animiert wird, enthält es denselben Wert wie pathSegList. |
| [PathSegList](../../aspose.svg.paths/isvganimatedpathdata/pathseglist/) { get; } | Bietet Zugriff auf die Basis‑ (d. h. statischen) Inhalte des ‘d’-Attributs in einer Form, die eins‑zu‑eins mit der SVG‑Syntax übereinstimmt. Wenn das ‘d’-Attribut also einen „absoluten moveto (M)“ und einen „absoluten arcto (A)“ Befehl enthält, wird pathSegList zwei Einträge haben: ein SVG_PATHSEG_MOVETO_ABS und ein SVG_PATHSEG_ARC_ABS. |

### Siehe auch

* namespace [Aspose.Svg.Paths](../../aspose.svg.paths/)
* assembly [Aspose.SVG](../../)
