---
title: "SVGScriptElementBuilder 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Builder.SVGScriptElementBuilder 类。用于构建 SVG 脚本元素的构建器类。script 元素用于在 SVG 文档中嵌入或引用可执行脚本。此类提供设置脚本元素特定属性的方法，如 type、source 和跨域设置。"
type: docs
weight: 1600
url: /zh/net/aspose.svg.builder/svgscriptelementbuilder/
---
## SVGScriptElementBuilder class

用于构建 SVG 'script' 元素的构建器类。'script' 元素用于在 SVG 文档中嵌入或引用可执行脚本。此类提供设置 'script' 元素特定属性的方法，如 type、src 和跨域设置。

```csharp
public class SVGScriptElementBuilder : SVGElementBuilder<SVGScriptElement>, ICoreAttributeSetter, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SVGScriptElementBuilder](svgscriptelementbuilder/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGScriptElement](../../aspose.svg/svgscriptelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Crossorigin](../../aspose.svg.builder/svgscriptelementbuilder/crossorigin/)(*string*) | 设置 SVG 'script' 元素的 'crossorigin' 属性，指定外部脚本的 CORS 设置。 |
| [Href](../../aspose.svg.builder/svgscriptelementbuilder/href/)(*string*) | 设置 SVG 'script' 元素的 'href' 属性，指定外部脚本文件的 URL。 |
| [Type](../../aspose.svg.builder/svgscriptelementbuilder/type/)(*string*) | 设置 SVG 'script' 元素的 'type' 属性，指定脚本语言类型（例如 "text/javascript"）。 |

### 另请参阅

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGScriptElement](../../aspose.svg/svgscriptelement/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
