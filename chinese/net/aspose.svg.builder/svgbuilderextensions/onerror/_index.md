---
title: "SVGBuilderExtensions.OnError"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions OnError 方法。设置元素的 onerror 事件属性，以处理错误事件"
type: docs
weight: 1430
url: /zh/net/aspose.svg.builder/svgbuilderextensions/onerror/
---
## SVGBuilderExtensions.OnError<TBuilder> method

设置 'onerror' 事件属性，以处理元素上的错误事件。

```csharp
public static TBuilder OnError<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, ICommonEventAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | SVG 元素构建器。 |
| value | 错误发生时要执行的 JavaScript 函数或脚本。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICommonEventAttributeSetter](../../icommoneventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
