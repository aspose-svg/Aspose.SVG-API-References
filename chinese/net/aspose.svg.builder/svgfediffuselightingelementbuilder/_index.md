---
title: "SVGFEDiffuseLightingElementBuilder 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Builder.SVGFEDiffuseLightingElementBuilder 类。用于创建 SVG feDiffuseLighting 元素的构建器类，这些元素在 SVG 滤镜中用于应用漫反射光照效果"
type: docs
weight: 1240
url: /zh/net/aspose.svg.builder/svgfediffuselightingelementbuilder/
---
## SVGFEDiffuseLightingElementBuilder class

用于创建 SVG 'feDiffuseLighting' 元素的构建器类，用于 SVG 滤镜以应用漫反射光照效果。

```csharp
public class SVGFEDiffuseLightingElementBuilder : 
    SVGFEBaseLightingElementBuilder<SVGFEDiffuseLightingElement, SVGFEDiffuseLightingElementBuilder>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SVGFEDiffuseLightingElementBuilder](svgfediffuselightingelementbuilder/)() | 默认构造函数。 |

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
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFEDiffuseLightingElement](../../aspose.svg.filters/svgfediffuselightingelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [DiffuseConstant](../../aspose.svg.builder/svgfediffuselightingelementbuilder/diffuseconstant/)(*double*) | 设置 feDiffuseLighting 元素的 'diffuseConstant' 属性。 |
| [KernelUnitLength](../../aspose.svg.builder/svgfediffuselightingelementbuilder/kernelunitlength/)(*double, double?*) | 设置 feDiffuseLighting 元素的 'kernelUnitLength' 属性。 |
| [SurfaceScale](../../aspose.svg.builder/svgfediffuselightingelementbuilder/surfacescale/)(*double*) | 设置 feDiffuseLighting 元素的 'surfaceScale' 属性。 |
| [WithFeDistantLight](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/withfedistantlight/)(*Action&lt;SVGFEDistantLightElementBuilder&gt;*) |  |
| [WithFePointLight](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/withfepointlight/)(*Action&lt;SVGFEPointLightElementBuilder&gt;*) |  |
| [WithFeSpotLight](../../aspose.svg.builder/svgfebaselightingelementbuilder-2/withfespotlight/)(*Action&lt;SVGFESpotLightElementBuilder&gt;*) |  |

### 另请参阅

* class [SVGFEBaseLightingElementBuilder&lt;TElement,TBuilder&gt;](../svgfebaselightingelementbuilder-2/)
* class [SVGFEDiffuseLightingElement](../../aspose.svg.filters/svgfediffuselightingelement/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
