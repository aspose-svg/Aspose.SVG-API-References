---
title: "SVGFEColorMatrixElementBuilder.TypeAndValues"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGFEColorMatrixElementBuilder TypeAndValues-metod. Ställer in typ- och värdeattributen för feColorMatrix-elementet som specificerar färgmatrisoperationen och dess parametrar"
type: docs
weight: 30
url: /sv/net/aspose.svg.builder/svgfecolormatrixelementbuilder/typeandvalues/
---
## SVGFEColorMatrixElementBuilder.TypeAndValues method

Ställer in attributen 'type' och 'values' för feColorMatrix-elementet, vilket specificerar färgmatrisoperationen och dess parametrar.

```csharp
public SVGFEColorMatrixElementBuilder TypeAndValues(ColorMatrixOperation type, 
    params double[] values)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | ColorMatrixOperation | ColorMatrixOperation‑enumvärdet som representerar typen av färgmatrisoperation. |
| values | Double[] | Parametrarna för färgmatrisoperationen. |

### Returvärde

Den aktuella byggarinstansen.

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Kastas när de angivna värdena inte uppfyller kraven för den specificerade typen. |
| NotSupportedException | Kastas när en ej stödjad matrisoperationstyp tillhandahålls. |

### Se även

* enum [ColorMatrixOperation](../../colormatrixoperation/)
* class [SVGFEColorMatrixElementBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
