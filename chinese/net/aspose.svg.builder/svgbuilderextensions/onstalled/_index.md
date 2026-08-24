---
title: "SVGBuilderExtensions.OnStalled"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions OnStalled 方法。设置 onstalled 事件属性，以处理媒体数据传输意外中止时的事件"
type: docs
weight: 1780
url: /zh/net/aspose.svg.builder/svgbuilderextensions/onstalled/
---
## SVGBuilderExtensions.OnStalled<TBuilder> method

设置 'onstalled' 事件属性，以处理媒体数据传输意外中止时的事件。

```csharp
public static TBuilder OnStalled<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | SVG 元素构建器。 |
| value | 当媒体数据传输暂停时要执行的 JavaScript 函数或脚本。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
