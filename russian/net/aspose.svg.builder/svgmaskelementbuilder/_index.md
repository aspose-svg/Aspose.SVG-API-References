---
title: "Класс SVGMaskElementBuilder"
second_title: "Aspose.SVG для .NET справочник API"
description: "Aspose.Svg.Builder.SVGMaskElementBuilder класс. Класс‑строитель для создания элемента маски SVG, который используется для определения альфа‑маски при композитинге текущего объекта с фоном. Этот класс позволяет создавать содержимое внутри элемента маски и предоставляет методы для установки различных атрибутов, специфичных для элемента маски в SVG."
type: docs
weight: 1510
url: /ru/net/aspose.svg.builder/svgmaskelementbuilder/
---
## SVGMaskElementBuilder class

Класс‑строитель для создания элемента SVG 'mask', который используется для определения альфа‑маски при композитинге текущего объекта с фоном. Этот класс позволяет формировать содержимое внутри элемента 'mask' и предоставляет методы для установки различных атрибутов, специфичных для элемента 'mask' в SVG.

```csharp
public class SVGMaskElementBuilder : SVGElementBuilder<SVGMaskElement>, ICompositeElementBuilder, 
    IConditionalProcessingAttributeSetter, ICoreAttributeSetter, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter, 
    IPresentationAttributeSetter, IRectAttributeSetter
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SVGMaskElementBuilder](svgmaskelementbuilder/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Методы

| Имя | Описание |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGMaskElement](../../aspose.svg/svgmaskelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [MaskContentUnits](../../aspose.svg.builder/svgmaskelementbuilder/maskcontentunits/)(*[CoordinateUnits](../coordinateunits/)*) | Устанавливает атрибут 'maskContentUnits' элемента SVG 'mask', указывая систему координат для содержимого маски. |
| [MaskUnits](../../aspose.svg.builder/svgmaskelementbuilder/maskunits/)(*[CoordinateUnits](../coordinateunits/)*) | Устанавливает атрибут 'maskUnits' элемента SVG 'mask', указывая систему координат для атрибутов маски. |

### См. также

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGMaskElement](../../aspose.svg/svgmaskelement/)
* interface [ICompositeElementBuilder](../icompositeelementbuilder/)
* interface [IConditionalProcessingAttributeSetter](../iconditionalprocessingattributesetter/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
