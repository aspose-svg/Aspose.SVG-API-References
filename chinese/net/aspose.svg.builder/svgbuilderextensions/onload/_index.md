---
title: "SVGBuilderExtensions.OnLoad"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions OnLoad 方法。设置 onload 事件属性，以处理元素的加载事件"
type: docs
weight: 1520
url: /zh/net/aspose.svg.builder/svgbuilderextensions/onload/
---
## SVGBuilderExtensions.OnLoad<TBuilder> method

设置元素的 'onload' 事件属性，以处理加载事件。

```csharp
public static TBuilder OnLoad<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | SVG 元素构建器。 |
| value | 当元素加载完成时要执行的 JavaScript 函数或脚本。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
