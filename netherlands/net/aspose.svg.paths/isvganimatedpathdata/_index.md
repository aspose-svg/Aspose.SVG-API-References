---
title: "ISVGAnimatedPathData Interface"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Paths.ISVGAnimatedPathData interface. De SVGAnimatedPathData interface ondersteunt elementen die een d-attribuut hebben dat SVG-padgegevens bevat en ondersteunt de mogelijkheid om dat attribuut te animeren"
type: docs
weight: 4550
url: /nl/net/aspose.svg.paths/isvganimatedpathdata/
---
## ISVGAnimatedPathData interface

De SVGAnimatedPathData interface ondersteunt elementen die een ‘d’-attribuut hebben dat SVG-padgegevens bevat, en ondersteunt de mogelijkheid om dat attribuut te animeren.

```csharp
public interface ISVGAnimatedPathData
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AnimatedPathSegList](../../aspose.svg.paths/isvganimatedpathdata/animatedpathseglist/) { get; } | Biedt toegang tot de huidige geanimeerde inhoud van het ‘d’-attribuut in een vorm die één-op-één overeenkomt met de syntaxis van SVG. Als het opgegeven attribuut of de eigenschap wordt geanimeerd, bevat het de huidige geanimeerde waarde van het attribuut of de eigenschap, en zowel het object zelf als de inhoud zijn alleen-lezen. Als het opgegeven attribuut of de eigenschap momenteel niet wordt geanimeerd, bevat het dezelfde waarde als pathSegList. |
| [PathSegList](../../aspose.svg.paths/isvganimatedpathdata/pathseglist/) { get; } | Biedt toegang tot de basis (d.w.z. statische) inhoud van het ‘d’-attribuut in een vorm die één-op-één overeenkomt met de syntaxis van SVG. Dus, als het ‘d’-attribuut een "absolute moveto (M)" en een "absolute arcto (A)" opdracht heeft, zal pathSegList twee items bevatten: een SVG_PATHSEG_MOVETO_ABS en een SVG_PATHSEG_ARC_ABS. |

### Zie ook

* namespace [Aspose.Svg.Paths](../../aspose.svg.paths/)
* assembly [Aspose.SVG](../../)
