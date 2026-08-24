---
title: "SVGBuilderExtensions.TextDecoration"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions TextDecoration 方法。设置 SVG 元素的 text-decoration 属性，定义添加到文本的装饰"
type: docs
weight: 2210
url: /zh/net/aspose.svg.builder/svgbuilderextensions/textdecoration/
---
## SVGBuilderExtensions.TextDecoration<TBuilder> method

为 SVG 元素设置 'text-decoration' 属性，定义添加到文本的装饰。

```csharp
public static TBuilder TextDecoration<TBuilder>(this TBuilder builder, bool underline = false, 
    bool overline = false, bool lineThrough = false, bool blink = false)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | 构建器实例。 |
| 下划线 | 指定文本是否应加下划线。 |
| 上划线 | 指定文本是否应有上划线。 |
| 删除线 | 指定文本是否应有删除线。 |
| 闪烁 | 指定文本是否应闪烁（不推荐使用）。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
