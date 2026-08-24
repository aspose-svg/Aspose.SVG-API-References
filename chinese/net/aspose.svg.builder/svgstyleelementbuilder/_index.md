---
title: "SVGStyleElementBuilder 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Builder.SVGStyleElementBuilder 类。用于构建 SVG 样式元素的生成器类。此类便于创建和配置带有 CSS 规则的 SVG 样式元素。"
type: docs
weight: 1630
url: /zh/net/aspose.svg.builder/svgstyleelementbuilder/
---
## SVGStyleElementBuilder class

用于构建 SVG 'style' 元素的构建器类。此类便于使用 CSS 规则创建和配置 SVG style 元素。

```csharp
public class SVGStyleElementBuilder : SVGElementBuilder<SVGStyleElement>, ICoreAttributeSetter, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SVGStyleElementBuilder](svgstyleelementbuilder/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddComment](../../aspose.svg.builder/svgstyleelementbuilder/addcomment/)(*string*) | 向样式内容添加注释。 |
| [AddRule](../../aspose.svg.builder/svgstyleelementbuilder/addrule/#addrule)(*string, Action&lt;RuleBuilder&gt;*) | 使用 RuleBuilder 向样式元素添加 CSS 规则。 |
| [AddRule](../../aspose.svg.builder/svgstyleelementbuilder/addrule/#addrule_1)(*string, string*) | 向样式元素添加 CSS 规则。 |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| override [Build](../../aspose.svg.builder/svgstyleelementbuilder/build/#build)(*[Document](../../aspose.svg.dom/document/)*) | 构建带有累计 CSS 规则的 SVG 样式元素并将其添加到指定的文档中。 |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGStyleElement](../../aspose.svg/svgstyleelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Media](../../aspose.svg.builder/svgstyleelementbuilder/media/)(*string*) | 设置 SVG 'style' 元素的 'media' 属性。此属性指定样式所针对的媒体，使样式能够根据媒体类型进行条件化。 |
| [Title](../../aspose.svg.builder/svgstyleelementbuilder/title/)(*string*) | 设置 SVG 'style' 元素的 'title' 属性。此属性为样式元素提供建议性标题，可用于辅助功能和工具提示文本。 |
| [Type](../../aspose.svg.builder/svgstyleelementbuilder/type/)(*string*) | 设置 SVG 'style' 元素的 'type' 属性。此属性指定元素内容的样式表语言。 |

### 另请参阅

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGStyleElement](../../aspose.svg/svgstyleelement/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
