---
title: "SVGGraphicsElement.GetScreenCTM"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGGraphicsElement GetScreenCTM method. Returnerar transformationsmatrisen från aktuella användarenheter, d.v.s. efter tillämpning av attributet transform om det finns, till förälderns användaragents uppfattning av en pixel. För displayenheter representerar detta idealiskt en fysisk skärm‑pixel. För andra enheter eller miljöer där fysiska pixelformat är okända kan en algoritm liknande CSS2‑definitionen av en pixel användas istället. Observera att null returneras om detta element inte är kopplat till dokumentträdet. Denna metod skulle ha kunnat heta getClientCTM, men namnet getScreenCTM behålls av historiska skäl."
type: docs
weight: 90
url: /sv/net/aspose.svg/svggraphicselement/getscreenctm/
---
## SVGGraphicsElement.GetScreenCTM method

Returnerar transformationsmatrisen från aktuella användarenheter (dvs. efter tillämpning av attributet ‘transform’, om någon) till den överordnade användaragenterens definition av en \"pixel\". För visningsenheter representerar detta idealiskt en fysisk skärm‑pixel. För andra enheter eller miljöer där fysiska pixelformat är okända kan en algoritm liknande CSS2‑definitionen av en \"pixel\" användas istället. Observera att null returneras om detta element inte är kopplat till dokumentträdet. Denna metod skulle ha kunnat heta getClientCTM, men namnet getScreenCTM behålls av historiska skäl.

```csharp
public SVGMatrix GetScreenCTM()
```

### Returvärde

Ett SVGMatrix‑objekt som definierar den angivna transformationsmatrisen.

### Se även

* class [SVGMatrix](../../../aspose.svg.datatypes/svgmatrix/)
* class [SVGGraphicsElement](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
