---
title: "SVGBuilderExtensions.OnSeeking"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions OnSeeking 方法。设置 onseeking 事件属性，以在媒体的定位操作开始时处理事件。"
type: docs
weight: 1750
url: /zh/net/aspose.svg.builder/svgbuilderextensions/onseeking/
---
## SVGBuilderExtensions.OnSeeking<TBuilder> method

设置 'onseeking' 事件属性，以处理媒体定位操作开始时的事件。

```csharp
public static TBuilder OnSeeking<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | SVG 元素构建器。 |
| value | 在定位操作开始时执行的 JavaScript 函数或脚本。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
