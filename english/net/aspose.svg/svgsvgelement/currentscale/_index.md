---
title: SVGSVGElement.CurrentScale
second_title: Aspose.SVG for .NET API Reference
description: SVGSVGElement property. On an outermost svg element this attribute indicates the current scale factor relative to the initial view to take into account user magnification and panning operations as described under Magnification and panning. DOM attributes currentScale and currentTranslate are equivalent to the 2x3 matrix a b c d e f  currentScale 0 0 currentScale currentTranslate.x currentTranslate.y. If magnification is enabled i.e. zoomAndPanmagnify then the effect is as if an extra transformation were placed at the outermost level on the SVG document fragment i.e. outside the outermost svg element. When accessed on an svg element that is not an outermost svg element it is undefined what behavior this attribute has
type: docs
weight: 10
url: /net/aspose.svg/svgsvgelement/currentscale/
---
## SVGSVGElement.CurrentScale property

On an outermost svg element, this attribute indicates the current scale factor relative to the initial view to take into account user magnification and panning operations, as described under Magnification and panning. DOM attributes currentScale and currentTranslate are equivalent to the 2x3 matrix [a b c d e f] = [currentScale 0 0 currentScale currentTranslate.x currentTranslate.y]. If "magnification" is enabled (i.e., zoomAndPan="magnify"), then the effect is as if an extra transformation were placed at the outermost level on the SVG document fragment (i.e., outside the outermost svg element). When accessed on an ‘svg’ element that is not an outermost svg element, it is undefined what behavior this attribute has.

```csharp
public float CurrentScale { get; set; }
```

### Property Value

The current scale.

### See Also

* class [SVGSVGElement](../)
* namespace [Aspose.Svg](../../svgsvgelement/)
* assembly [Aspose.SVG](../../../)
