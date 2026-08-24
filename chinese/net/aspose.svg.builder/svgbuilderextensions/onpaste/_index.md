---
title: "SVGBuilderExtensions.OnPaste"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions OnPaste 方法。设置 onpaste 事件属性，定义在内容粘贴到 SVG 元素时运行的脚本。"
type: docs
weight: 1640
url: /zh/net/aspose.svg.builder/svgbuilderextensions/onpaste/
---
## SVGBuilderExtensions.OnPaste<TBuilder> method

设置 'onpaste' 事件属性，定义在内容粘贴到 SVG 元素时运行的脚本。

```csharp
public static TBuilder OnPaste<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IDocumentElementEventAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | SVG 元素构建器。 |
| value | 在粘贴事件上执行的 JavaScript 函数或脚本。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../../idocumentelementeventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
