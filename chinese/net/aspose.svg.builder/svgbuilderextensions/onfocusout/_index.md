---
title: "SVGBuilderExtensions.OnFocusOut"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions OnFocusOut 方法。设置 onfocusout 事件属性，以处理元素失去焦点的事件。"
type: docs
weight: 1460
url: /zh/net/aspose.svg.builder/svgbuilderextensions/onfocusout/
---
## SVGBuilderExtensions.OnFocusOut<TBuilder> method

设置元素的 'onfocusout' 事件属性，以处理焦点离开事件。

```csharp
public static TBuilder OnFocusOut<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGraphicalEventAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | SVG 元素构建器。 |
| value | 元素失去焦点时要执行的 JavaScript 函数或脚本，通常在 ‘onblur’ 事件之前。 |

### 返回值

用于链式调用的构建器实例。

## 备注

当元素即将失去焦点时，会触发 'onfocusout' 事件。类似于 'onfocusin'，此事件支持冒泡，并且也可用于检测子元素的焦点变化。

### 另请参阅

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGraphicalEventAttributeSetter](../../igraphicaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
