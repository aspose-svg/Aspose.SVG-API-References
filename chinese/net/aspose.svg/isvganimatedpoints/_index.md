---
title: "ISVGAnimatedPoints 接口"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.ISVGAnimatedPoints 接口。SVGAnimatedPoints 接口支持具有 points 属性的元素，该属性保存坐标值列表，并支持对该属性进行动画化。此外，通过 XML DOM（例如使用 getAttribute 方法）访问的原始元素的 points 属性将反映对 points 所做的任何更改。"
type: docs
weight: 4070
url: /zh/net/aspose.svg/isvganimatedpoints/
---
## ISVGAnimatedPoints interface

SVGAnimatedPoints 接口支持具有 ‘points’ 属性的元素，该属性保存坐标值列表并支持对该属性进行动画化。此外，通过 XML DOM（例如，使用 getAttribute() 方法调用）访问的原始元素上的 ‘points’ 属性将反映对 points 所做的任何更改。

```csharp
public interface ISVGAnimatedPoints
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AnimatedPoints](../../aspose.svg/isvganimatedpoints/animatedpoints/) { get; } | 提供对 ‘points’ 属性当前动画内容的访问。如果给定的属性或属性正在动画中，则包含该属性或属性的当前动画值。如果给定的属性或属性当前未动画，则包含与 points 相同的值。 |
| [Points](../../aspose.svg/isvganimatedpoints/points/) { get; } | 提供对 ‘points’ 属性基础（即静态）内容的访问。 |

### 另请参阅

* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)
