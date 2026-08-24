---
title: "SVGFEBlendElementBuilder 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Builder.SVGFEBlendElementBuilder 类。用于创建 SVG 过滤器中使用的 feBlend 元素的构建器类"
type: docs
weight: 1190
url: /zh/net/aspose.svg.builder/svgfeblendelementbuilder/
---
## SVGFEBlendElementBuilder class

用于创建 SVG 'feBlend' 元素的构建器类，用于 SVG 滤镜。

```csharp
public class SVGFEBlendElementBuilder : SVGElementBuilder<SVGFEBlendElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IFilterPrimitiveInAttributeSetter, IPresentationAttributeSetter
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SVGFEBlendElementBuilder](svgfeblendelementbuilder/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgfeblendelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | 向 feBlend 元素添加脚本配置。 |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFEBlendElement](../../aspose.svg.filters/svgfeblendelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [In2](../../aspose.svg.builder/svgfeblendelementbuilder/in2/#in2)(*[FilterInput](../filterinput/)*) | 设置 feBlend 元素的 'in2' 属性，指定混合操作的第二个输入。 |
| [In2](../../aspose.svg.builder/svgfeblendelementbuilder/in2/#in2_1)(*string*) | 设置 feBlend 元素的 'in2' 属性，指定混合操作的第二个输入。 |
| [Mode](../../aspose.svg.builder/svgfeblendelementbuilder/mode/)(*[BlendMode](../blendmode/)*) | 设置 feBlend 元素的 'mode' 属性，指定要使用的混合模式。 |

### 另请参阅

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGFEBlendElement](../../aspose.svg.filters/svgfeblendelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../ifilterprimitiveinattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
