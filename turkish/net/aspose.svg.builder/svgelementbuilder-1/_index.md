---
title: "SVGElementBuilderT Sınıfı"
second_title: "Aspose.SVG for .NET API Reference"
description: "Aspose.Svg.Builder.SVGElementBuilder1T sınıfı. T türündeki SVG öğelerini oluşturmak için temel bir sınıfı temsil eder."
type: docs
weight: 1160
url: /tr/net/aspose.svg.builder/svgelementbuilder-1/
---
## SVGElementBuilder<T> class

*T* tipinde SVG öğeleri oluşturmak için temel sınıfı temsil eder.

```csharp
public abstract class SVGElementBuilder<T> : ISVGElementBuilder
    where T : SVGElement
```

| Parametre | Açıklama |
| --- | --- |
| T | Bu yapıcının oluşturmasından sorumlu olduğu SVG öğesinin türü. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } | SVG öğesine uygulanacak yapılandırma listesini alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) | SVG öğesine bir özellik yapılandırması ekler. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/#build)(*[Document](../../aspose.svg.dom/document/)*) | SVG öğesini oluşturur ve tüm yapılandırmaları ona uygular. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/#build_1)(*T*) | Mevcut bir SVG öğesine yapılandırmaları uygular. |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) | SVG öğesini genel bir SVGElement olarak oluşturur. |

### Ayrıca Bakınız

* interface [ISVGElementBuilder](../isvgelementbuilder/)
* class [SVGElement](../../aspose.svg/svgelement/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
