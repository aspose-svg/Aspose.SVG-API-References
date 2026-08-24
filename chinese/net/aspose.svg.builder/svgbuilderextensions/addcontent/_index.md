---
title: "SVGBuilderExtensions.AddContent"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions AddContent 方法。向 SVG 元素添加文本内容。"
type: docs
weight: 90
url: /zh/net/aspose.svg.builder/svgbuilderextensions/addcontent/
---
## SVGBuilderExtensions.AddContent<TBuilder> method

向 SVG 元素添加文本内容。

```csharp
public static TBuilder AddContent<TBuilder>(this TBuilder builder, string text)
    where TBuilder : ISVGElementBuilder, ITextContentSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | SVG 元素构建器。 |
| 文本 | 要添加到元素的文本。 |

### 返回值

用于链式调用的构建器实例。

## 备注

此方法允许直接向 SVG 元素添加文本内容。对于包含文本数据的元素非常有用。

### 另请参阅

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentSetter](../../itextcontentsetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
