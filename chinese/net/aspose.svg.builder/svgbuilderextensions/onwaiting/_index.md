---
title: "SVGBuilderExtensions.OnWaiting"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions OnWaiting 方法。设置 onwaiting 事件属性，以处理因数据缓冲导致媒体播放延迟的事件"
type: docs
weight: 1850
url: /zh/net/aspose.svg.builder/svgbuilderextensions/onwaiting/
---
## SVGBuilderExtensions.OnWaiting<TBuilder> method

设置 'onwaiting' 事件属性，以处理因数据缓冲导致媒体播放延迟时的事件。

```csharp
public static TBuilder OnWaiting<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | SVG 元素构建器。 |
| value | 媒体播放因缓冲而延迟时要执行的 JavaScript 函数或脚本。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
