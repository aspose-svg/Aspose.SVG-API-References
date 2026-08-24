---
title: "SVGBuilderExtensions.OnFocusIn"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions OnFocusIn 方法。设置 onfocusin 事件属性以处理元素上的 focus-in 事件"
type: docs
weight: 1450
url: /zh/net/aspose.svg.builder/svgbuilderextensions/onfocusin/
---
## SVGBuilderExtensions.OnFocusIn<TBuilder> method

设置 'onfocusin' 事件属性，以处理元素上的获取焦点事件。

```csharp
public static TBuilder OnFocusIn<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGraphicalEventAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | SVG 元素构建器。 |
| value | 当元素获得焦点时要执行的 JavaScript 函数或脚本，通常在 'onfocus' 事件之前。 |

### 返回值

用于链式调用的构建器实例。

## 备注

当元素即将获得焦点时会触发 'onfocusin' 事件。该事件不同于 'onfocus'，因为它支持冒泡，并且可用于检测子元素的焦点变化。

### 另请参阅

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGraphicalEventAttributeSetter](../../igraphicaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
