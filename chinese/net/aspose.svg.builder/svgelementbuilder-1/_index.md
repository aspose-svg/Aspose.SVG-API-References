---
title: "SVGElementBuilderT 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Builder.SVGElementBuilder1T 类。表示用于构建类型为 T 的 SVG 元素的基类"
type: docs
weight: 1160
url: /zh/net/aspose.svg.builder/svgelementbuilder-1/
---
## SVGElementBuilder<T> class

表示用于构建类型为 *T* 的 SVG 元素的基类。

```csharp
public abstract class SVGElementBuilder<T> : ISVGElementBuilder
    where T : SVGElement
```

| 参数 | 描述 |
| --- | --- |
| T | 此构建器负责创建的 SVG 元素类型。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } | 获取要应用于 SVG 元素的配置列表。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) | 向 SVG 元素添加属性配置。 |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/#build)(*[Document](../../aspose.svg.dom/document/)*) | 构建 SVG 元素并将所有配置应用于它。 |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/#build_1)(*T*) | 将配置应用于现有的 SVG 元素。 |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) | 将 SVG 元素构建为通用的 SVGElement。 |

### 另请参阅

* interface [ISVGElementBuilder](../isvgelementbuilder/)
* class [SVGElement](../../aspose.svg/svgelement/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
