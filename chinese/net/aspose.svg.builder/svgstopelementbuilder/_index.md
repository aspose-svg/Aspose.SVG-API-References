---
title: "SVGStopElementBuilder 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Builder.SVGStopElementBuilder 类。用于构建 SVG stop 元素的构建器类。stop 元素在渐变定义（线性或径向）中用于定义颜色停止点。该类提供方法设置 stop 元素的各种特定属性，如 offset 和颜色。"
type: docs
weight: 1620
url: /zh/net/aspose.svg.builder/svgstopelementbuilder/
---
## SVGStopElementBuilder class

用于构建 SVG 'stop' 元素的构建器类。'stop' 元素在渐变定义（线性或径向）中用于定义颜色停点。此类提供设置 'stop' 元素特定属性的方法，如 offset 和颜色。

```csharp
public class SVGStopElementBuilder : SVGElementBuilder<SVGStopElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDocumentElementEventAttributeSetter, 
    IGlobalEventAttributeSetter, IPresentationAttributeSetter
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SVGStopElementBuilder](svgstopelementbuilder/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgstopelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | 向 SVG 'stop' 元素添加脚本配置。 |
| [AddStyle](../../aspose.svg.builder/svgstopelementbuilder/addstyle/)(*Action&lt;SVGStyleElementBuilder&gt;*) | 向 SVG 'stop' 元素添加样式配置。 |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGStopElement](../../aspose.svg/svgstopelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Offset](../../aspose.svg.builder/svgstopelementbuilder/offset/)(*double, [StopUnitType](../stopunittype/)*) | 设置 SVG 'stop' 元素的 'offset' 属性，指定渐变中颜色停止点的位置。 |

### 另请参阅

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGStopElement](../../aspose.svg/svgstopelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
