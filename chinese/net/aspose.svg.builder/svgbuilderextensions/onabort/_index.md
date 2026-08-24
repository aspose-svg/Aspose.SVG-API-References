---
title: "SVGBuilderExtensions.OnAbort"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions OnAbort 方法。设置 onabort 事件属性，定义在 SVG 文档加载被中止时运行的脚本。"
type: docs
weight: 1190
url: /zh/net/aspose.svg.builder/svgbuilderextensions/onabort/
---
## SVGBuilderExtensions.OnAbort<TBuilder> method

设置 'onabort' 事件属性，定义在 SVG 文档加载被中止时要运行的脚本。

```csharp
public static TBuilder OnAbort<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IDocumentEventAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | SVG 元素构建器。 |
| value | 文档加载被中止时要执行的 JavaScript 函数或脚本。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDocumentEventAttributeSetter](../../idocumenteventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
