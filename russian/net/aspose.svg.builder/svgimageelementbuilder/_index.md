---
title: "Класс SVGImageElementBuilder"
second_title: "Aspose.SVG для .NET справочник API"
description: "Класс Aspose.Svg.Builder.SVGImageElementBuilder. Класс‑строитель для создания элемента SVG image. Этот элемент используется для встраивания изображений в графику SVG. Он предоставляет методы для установки различных атрибутов, специфичных для элемента изображения, и для добавления дополнительных конфигураций, таких как обрезные пути, маски, стили и скрипты."
type: docs
weight: 1470
url: /ru/net/aspose.svg.builder/svgimageelementbuilder/
---
## SVGImageElementBuilder class

Класс‑строитель для создания элемента SVG 'image'. Этот элемент используется для встраивания изображений в графику SVG. Он предоставляет методы для установки различных атрибутов, специфичных для элемента 'image', и для добавления дополнительных конфигураций, таких как обрезающие пути, маски, стили и скрипты.

```csharp
public class SVGImageElementBuilder : SVGElementBuilder<SVGImageElement>, IAnimationElementBuilder, 
    ICompositeAttributeSetter, IDescriptiveElementBuilder, IPreserveAspectRatioAttributeSetter, 
    IRectAttributeSetter
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SVGImageElementBuilder](svgimageelementbuilder/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Методы

| Имя | Описание |
| --- | --- |
| [AddClipPath](../../aspose.svg.builder/svgimageelementbuilder/addclippath/)(*Action&lt;SVGClipPathElementBuilder&gt;*) | Добавляет конфигурацию обрезного пути к элементу SVG 'image'. |
| [AddMask](../../aspose.svg.builder/svgimageelementbuilder/addmask/)(*Action&lt;SVGMaskElementBuilder&gt;*) | Добавляет конфигурацию маски к элементу SVG 'image'. |
| [AddScript](../../aspose.svg.builder/svgimageelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | Добавляет конфигурацию скрипта к элементу SVG 'image'. |
| [AddStyle](../../aspose.svg.builder/svgimageelementbuilder/addstyle/)(*Action&lt;SVGStyleElementBuilder&gt;*) | Добавляет конфигурацию стиля к элементу SVG 'image'. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGImageElement](../../aspose.svg/svgimageelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Href](../../aspose.svg.builder/svgimageelementbuilder/href/)(*string*) | Устанавливает атрибут 'href' элемента SVG 'image', указывая URL изображения для встраивания. |
| [HrefBase64FromBytes](../../aspose.svg.builder/svgimageelementbuilder/hrefbase64frombytes/)(*byte[], string*) | Устанавливает атрибут 'href' элемента SVG 'image', используя байты изображения, закодированные в base64. |
| [HrefBase64FromFile](../../aspose.svg.builder/svgimageelementbuilder/hrefbase64fromfile/#hrefbase64fromfile)(*string*) | Устанавливает атрибут 'href' элемента SVG 'image', используя файл изображения, закодированный в base64. |
| [HrefBase64FromFile](../../aspose.svg.builder/svgimageelementbuilder/hrefbase64fromfile/#hrefbase64fromfile_1)(*string, string*) | Устанавливает атрибут 'href' элемента SVG 'image', используя файл изображения, закодированный в base64, с указанным MIME‑типом. |

### См. также

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGImageElement](../../aspose.svg/svgimageelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IPreserveAspectRatioAttributeSetter](../ipreserveaspectratioattributesetter/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
