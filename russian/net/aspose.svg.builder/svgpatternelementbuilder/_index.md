---
title: "SVGPatternElementBuilder Класс"
second_title: "Aspose.SVG для .NET справочник API"
description: "Aspose.Svg.Builder.SVGPatternElementBuilder класс. Класс‑строитель для создания элемента SVG pattern, который используется для определения шаблона, применяемого для заполнения графических элементов внутри SVG. Этот класс предоставляет методы для установки различных атрибутов, специфичных для элемента pattern, и для построения его содержимого."
type: docs
weight: 1540
url: /ru/net/aspose.svg.builder/svgpatternelementbuilder/
---
## SVGPatternElementBuilder class

Класс‑строитель для создания элемента SVG 'pattern', который используется для определения шаблона, применяемого для заполнения графических элементов в SVG. Этот класс предоставляет методы для установки различных атрибутов, специфичных для элемента 'pattern', и для формирования его содержимого.

```csharp
public class SVGPatternElementBuilder : SVGElementBuilder<SVGPatternElement>, 
    ICompositeElementBuilder, ICoreAttributeSetter, IGlobalEventAttributeSetter, 
    IPresentationAttributeSetter, IPreserveAspectRatioAttributeSetter, IRectAttributeSetter, 
    IViewBoxAttributeSetter
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SVGPatternElementBuilder](svgpatternelementbuilder/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Методы

| Имя | Описание |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGPatternElement](../../aspose.svg/svgpatternelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Href](../../aspose.svg.builder/svgpatternelementbuilder/href/)(*string*) | Устанавливает атрибут 'href' элемента SVG 'pattern', указывая ссылку на другой шаблон, от которого этот шаблон наследует атрибуты. |
| [PatternContentUnits](../../aspose.svg.builder/svgpatternelementbuilder/patterncontentunits/)(*[CoordinateUnits](../coordinateunits/)*) | Устанавливает атрибут 'patternContentUnits' элемента SVG 'pattern', указывая систему координат для содержимого шаблона. |
| [PatternTransform](../../aspose.svg.builder/svgpatternelementbuilder/patterntransform/)(*Func&lt;TransformBuilder, TransformBuilder&gt;*) | Устанавливает атрибут 'patternTransform' элемента SVG 'pattern', применяя трансформацию к шаблону. |
| [PatternUnits](../../aspose.svg.builder/svgpatternelementbuilder/patternunits/)(*[CoordinateUnits](../coordinateunits/)*) | Устанавливает атрибут 'patternUnits' элемента SVG 'pattern', указывая систему координат для x, y, ширины и высоты шаблона. |

### См. также

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGPatternElement](../../aspose.svg/svgpatternelement/)
* interface [ICompositeElementBuilder](../icompositeelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* interface [IPreserveAspectRatioAttributeSetter](../ipreserveaspectratioattributesetter/)
* interface [IRectAttributeSetter](../irectattributesetter/)
* interface [IViewBoxAttributeSetter](../iviewboxattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
