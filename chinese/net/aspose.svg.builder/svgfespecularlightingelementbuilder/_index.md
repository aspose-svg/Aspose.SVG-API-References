---
title: "SVGFESpecularLightingElementBuilder 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Builder.SVGFESpecularLightingElementBuilder 类。用于创建 SVG feSpecularLighting 元素的构建器类，这些元素对图像应用镜面光照效果。"
type: docs
weight: 1400
url: /zh/net/aspose.svg.builder/svgfespecularlightingelementbuilder/
---
## SVGFESpecularLightingElementBuilder class

用于创建 SVG 'feSpecularLighting' 元素的构建器类，用于对图像应用镜面光照效果。

```csharp
public class SVGFESpecularLightingElementBuilder : 
    SVGFEBaseLightingElementBuilder<SVGFESpecularLightingElement, SVGFESpecularLightingElementBuilder>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SVGFESpecularLightingElementBuilder](svgfespecularlightingelementbuilder/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) |  |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| override [Build](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFESpecularLightingElement](../../aspose.svg.filters/svgfespecularlightingelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [KernelUnitLength](../../aspose.svg.builder/svgfespecularlightingelementbuilder/kernelunitlength/)(*double, double?*) | 设置 'kernelUnitLength' 属性，定义卷积核单元长度。 |
| [SpecularConstant](../../aspose.svg.builder/svgfespecularlightingelementbuilder/specularconstant/)(*double*) | 设置 'specularConstant' 属性，表示镜面反射常数。 |
| [SpecularExponent](../../aspose.svg.builder/svgfespecularlightingelementbuilder/specularexponent/)(*double*) | 设置 'specularExponent' 属性，控制高光的聚焦程度。 |
| [SurfaceScale](../../aspose.svg.builder/svgfespecularlightingelementbuilder/surfacescale/)(*double*) | 设置 feSpecularLighting 元素的 'surfaceScale' 属性，定义用于光照计算的表面高度。 |
| [WithFeDistantLight](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/withfedistantlight/)(*Action&lt;SVGFEDistantLightElementBuilder&gt;*) |  |
| [WithFePointLight](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/withfepointlight/)(*Action&lt;SVGFEPointLightElementBuilder&gt;*) |  |
| [WithFeSpotLight](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/withfespotlight/)(*Action&lt;SVGFESpotLightElementBuilder&gt;*) |  |

### 另请参阅

* class [SVGFEBaseLightingElementBuilder&lt;TElement,TBuilder&gt;](../svgfebaselightingelementbuilder-2/)
* class [SVGFESpecularLightingElement](../../aspose.svg.filters/svgfespecularlightingelement/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
