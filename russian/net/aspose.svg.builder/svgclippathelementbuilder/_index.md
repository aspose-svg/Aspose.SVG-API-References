---
title: "Класс SVGClipPathElementBuilder"
second_title: "Aspose.SVG для .NET справочник API"
description: "Класс Aspose.Svg.Builder.SVGClipPathElementBuilder. Класс‑строитель для создания элемента SVG clipPath, который используется для определения пути обрезки. Позволяет формировать содержимое внутри элемента clipPath и предоставляет методы для установки различных атрибутов, специфичных для элемента clipPath в SVG."
type: docs
weight: 1130
url: /ru/net/aspose.svg.builder/svgclippathelementbuilder/
---
## SVGClipPathElementBuilder class

Класс‑строитель для создания SVG‑элемента 'clipPath', который используется для определения обрезающего пути. Он позволяет формировать содержимое внутри элемента 'clipPath' и предоставляет методы для установки различных атрибутов, специфичных для элемента 'clipPath' в SVG.

```csharp
public class SVGClipPathElementBuilder : SVGElementBuilder<SVGClipPathElement>, 
    IAnimationElementBuilder, ICompositeAttributeSetter, IDescriptiveElementBuilder, 
    IShapeElementBuilder
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SVGClipPathElementBuilder](svgclippathelementbuilder/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Методы

| Имя | Описание |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgclippathelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | Добавляет элемент script в элемент clipPath. |
| [AddText](../../aspose.svg.builder/svgclippathelementbuilder/addtext/)(*Action&lt;SVGTextElementBuilder&gt;*) | Добавляет элемент text в элемент clipPath. |
| [AddUse](../../aspose.svg.builder/svgclippathelementbuilder/adduse/)(*Action&lt;SVGUseElementBuilder&gt;*) | Добавляет элемент 'use' в элемент clipPath. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGClipPathElement](../../aspose.svg/svgclippathelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [ClipPathUnits](../../aspose.svg.builder/svgclippathelementbuilder/clippathunits/)(*[CoordinateUnits](../coordinateunits/)*) | Устанавливает атрибут 'clipPathUnits' элемента SVG 'clipPath', указывая систему координат для пути обрезки. |

### См. также

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGClipPathElement](../../aspose.svg/svgclippathelement/)
* interface [IAnimationElementBuilder](../ianimationelementbuilder/)
* interface [ICompositeAttributeSetter](../icompositeattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IShapeElementBuilder](../ishapeelementbuilder/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
