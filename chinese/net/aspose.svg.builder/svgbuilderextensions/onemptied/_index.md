---
title: "SVGBuilderExtensions.OnEmptied"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions OnEmptied 方法。设置 onemptied 事件属性，用于处理媒体元素源被清空的情况"
type: docs
weight: 1400
url: /zh/net/aspose.svg.builder/svgbuilderextensions/onemptied/
---
## SVGBuilderExtensions.OnEmptied<TBuilder> method

设置 'onemptied' 事件属性，以处理媒体元素源的清空。

```csharp
public static TBuilder OnEmptied<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | SVG 元素构建器。 |
| value | 当媒体元素的源被清空时要执行的 JavaScript 函数或脚本。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
