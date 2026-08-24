---
title: "SVGSVGElement.CurrentScale"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGSVGElement CurrentScale 属性。 在最外层的 svg 元素上，此属性指示相对于初始视图的当前缩放因子，以考虑用户放大和平移操作，如在 “Magnification and panning” 中所述。 DOM 属性 currentScale 和 currentTranslate 等价于 2x3 矩阵 a b c d e f  currentScale 0 0 currentScale currentTranslate.x currentTranslate.y。 如果启用了放大，即 zoomAndPanmagnify，则效果相当于在 SVG 文档片段的最外层（即最外层 svg 元素之外）放置了额外的变换。当在非最外层的 svg 元素上访问时，此属性的行为未定义。"
type: docs
weight: 10
url: /zh/net/aspose.svg/svgsvgelement/currentscale/
---
## SVGSVGElement.CurrentScale property

在最外层的 svg 元素上，此属性指示相对于初始视图的当前缩放因子，以考虑用户的放大和平移操作，如“放大和平移”章节所述。DOM 属性 currentScale 和 currentTranslate 等价于 2x3 矩阵 [a b c d e f] = [currentScale 0 0 currentScale currentTranslate.x currentTranslate.y]。如果启用了“放大”（即 zoomAndPan=\"magnify\"），则效果相当于在 SVG 文档片段的最外层（即最外层 svg 元素之外）添加了额外的变换。当在不是最外层的 ‘svg’ 元素上访问时，此属性的行为未定义。

```csharp
public float CurrentScale { get; set; }
```

### Property Value

当前缩放。

### 另请参阅

* class [SVGSVGElement](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
