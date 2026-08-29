---
title: "SVGFEImageElementBuilder Класс"
second_title: "Aspose.SVG для .NET справочник API"
description: "Aspose.Svg.Builder.SVGFEImageElementBuilder класс. Класс‑строитель для создания элементов SVG feImage, которые определяют изображение, используемое другими примитивами фильтра."
type: docs
weight: 1340
url: /ru/net/aspose.svg.builder/svgfeimageelementbuilder/
---
## SVGFEImageElementBuilder class

Класс‑строитель для создания SVG‑элементов 'feImage', определяющих изображение, используемое другими примитивами фильтра.

```csharp
public class SVGFEImageElementBuilder : SVGElementBuilder<SVGFEImageElement>, 
    IAnimationElementBuilder, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IFilterPrimitiveAttributeSetter, IPresentationAttributeSetter, 
    IPreserveAspectRatioAttributeSetter, IXLinkAttributeSetter
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SVGFEImageElementBuilder](svgfeimageelementbuilder/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Методы

| Имя | Описание |
| --- | --- |
| [AddAnimateTransform](../../aspose.svg.builder/svgfeimageelementbuilder/addanimatetransform/)(*Action&lt;SVGAnimateTransformElementBuilder&gt;*) | Добавляет конфигурацию анимированного преобразования к элементу feImage. |
| [AddScript](../../aspose.svg.builder/svgfeimageelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | Добавляет конфигурацию скрипта к элементу feImage. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGFEImageElement](../../aspose.svg.filters/svgfeimageelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Href](../../aspose.svg.builder/svgfeimageelementbuilder/href/)(*string*) | Устанавливает атрибут 'href' элемента feImage, определяя URL изображения, которое будет использоваться. |

### См. также

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGFEImageElement](../../aspose.svg.filters/svgfeimageelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IFilterPrimitiveAttributeSetter](../ifilterprimitiveattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* interface [IPreserveAspectRatioAttributeSetter](../ipreserveaspectratioattributesetter/)
* interface [IXLinkAttributeSetter](../ixlinkattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
