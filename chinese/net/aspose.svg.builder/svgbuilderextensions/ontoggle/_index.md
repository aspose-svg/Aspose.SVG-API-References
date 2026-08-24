---
title: "SVGBuilderExtensions.OnToggle"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions OnToggle 方法。设置 ontoggle 事件属性，以在用户切换诸如 details 元素的控件时处理事件"
type: docs
weight: 1820
url: /zh/net/aspose.svg.builder/svgbuilderextensions/ontoggle/
---
## SVGBuilderExtensions.OnToggle<TBuilder> method

设置 'ontoggle' 事件属性，以处理用户切换控件时的事件，例如 `details` 元素。

```csharp
public static TBuilder OnToggle<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | SVG 元素构建器。 |
| value | 当控件被切换时要执行的 JavaScript 函数或脚本。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
