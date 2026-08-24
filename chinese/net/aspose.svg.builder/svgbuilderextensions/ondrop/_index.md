---
title: "SVGBuilderExtensions.OnDrop"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions OnDrop 方法。设置 ondrop 事件属性，以处理将项目拖放到有效放置目标上的情况"
type: docs
weight: 1380
url: /zh/net/aspose.svg.builder/svgbuilderextensions/ondrop/
---
## SVGBuilderExtensions.OnDrop<TBuilder> method

设置 'ondrop' 事件属性，以处理项目放置到有效放置目标上的操作。

```csharp
public static TBuilder OnDrop<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | SVG 元素构建器。 |
| value | 当项目被拖放到有效放置目标上时要执行的 JavaScript 函数或脚本。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
