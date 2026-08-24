---
title: "SVGBuilderExtensions.AddSwitch"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions AddSwitch 方法。向构建器添加 switch 元素配置"
type: docs
weight: 510
url: /zh/net/aspose.svg.builder/svgbuilderextensions/addswitch/
---
## SVGBuilderExtensions.AddSwitch<TBuilder> method

向构建器添加一个 'switch' 元素配置。

```csharp
public static TBuilder AddSwitch<TBuilder>(this TBuilder builder, 
    Action<SVGSwitchElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| 配置 | 针对 'switch' 元素的配置操作。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* class [SVGSwitchElementBuilder](../../svgswitchelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
