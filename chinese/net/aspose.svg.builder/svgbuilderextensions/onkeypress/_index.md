---
title: "SVGBuilderExtensions.OnKeyPress"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions OnKeyPress 方法。设置 onkeypress 事件属性，以处理元素上的按键事件。"
type: docs
weight: 1500
url: /zh/net/aspose.svg.builder/svgbuilderextensions/onkeypress/
---
## SVGBuilderExtensions.OnKeyPress<TBuilder> method

设置元素的 'onkeypress' 事件属性，以处理键按压事件。

```csharp
public static TBuilder OnKeyPress<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | SVG 元素构建器。 |
| value | 当键被按下并释放时要执行的 JavaScript 函数或脚本。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
