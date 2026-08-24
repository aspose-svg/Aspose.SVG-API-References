---
title: "SVGBuilderExtensions.OnUnload"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions OnUnload 方法。设置 onunload 事件属性，定义在 SVG 文档卸载时运行的脚本"
type: docs
weight: 1830
url: /zh/net/aspose.svg.builder/svgbuilderextensions/onunload/
---
## SVGBuilderExtensions.OnUnload<TBuilder> method

设置 'onunload' 事件属性，定义 SVG 文档卸载时要运行的脚本。

```csharp
public static TBuilder OnUnload<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IDocumentEventAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | SVG 元素构建器。 |
| value | 文档卸载时要执行的 JavaScript 函数或脚本。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDocumentEventAttributeSetter](../../idocumenteventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
