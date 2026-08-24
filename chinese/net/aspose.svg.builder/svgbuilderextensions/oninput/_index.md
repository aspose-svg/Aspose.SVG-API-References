---
title: "SVGBuilderExtensions.OnInput"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions OnInput 方法。设置 oninput 事件属性，以处理元素上的输入事件"
type: docs
weight: 1470
url: /zh/net/aspose.svg.builder/svgbuilderextensions/oninput/
---
## SVGBuilderExtensions.OnInput<TBuilder> method

设置元素的 'oninput' 事件属性，以处理输入事件。

```csharp
public static TBuilder OnInput<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | SVG 元素构建器。 |
| value | 元素接收用户输入时要执行的 JavaScript 函数或脚本。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
