---
title: "SVGBuilderExtensions.OnCopy"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions OnCopy 方法。设置 oncopy 事件属性，定义在从 SVG 元素复制内容时运行的脚本"
type: docs
weight: 1270
url: /zh/net/aspose.svg.builder/svgbuilderextensions/oncopy/
---
## SVGBuilderExtensions.OnCopy<TBuilder> method

设置 'oncopy' 事件属性，定义在从 SVG 元素复制内容时运行的脚本。

```csharp
public static TBuilder OnCopy<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IDocumentElementEventAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | SVG 元素构建器。 |
| value | 复制事件时要执行的 JavaScript 函数或脚本。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../../idocumentelementeventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
