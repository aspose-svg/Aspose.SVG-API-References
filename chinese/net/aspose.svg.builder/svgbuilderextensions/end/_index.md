---
title: "SVGBuilderExtensions.End"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions End 方法。设置 end 属性，定义动画何时结束。"
type: docs
weight: 790
url: /zh/net/aspose.svg.builder/svgbuilderextensions/end/
---
## SVGBuilderExtensions.End<TBuilder> method

设置 'end' 属性，定义动画何时结束。

```csharp
public static TBuilder End<TBuilder>(this TBuilder builder, Action<TimingValueBuilder> configure)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | SVG 元素构建器。 |
| 配置 | 用于配置计时值的委托。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* class [TimingValueBuilder](../../timingvaluebuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
