---
title: "SVGBuilderExtensions.OnCanPlayThrough"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions OnCanPlayThrough 方法。设置 oncanplaythrough 事件属性，以在不中断的情况下处理媒体的可播放性"
type: docs
weight: 1230
url: /zh/net/aspose.svg.builder/svgbuilderextensions/oncanplaythrough/
---
## SVGBuilderExtensions.OnCanPlayThrough<TBuilder> method

设置 'oncanplaythrough' 事件属性，以处理媒体在不中断情况下的可播放性。

```csharp
public static TBuilder OnCanPlayThrough<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | SVG 元素构建器。 |
| value | 当媒体能够连续播放至结束而不因缓冲而停止时要执行的 JavaScript 函数或脚本。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
