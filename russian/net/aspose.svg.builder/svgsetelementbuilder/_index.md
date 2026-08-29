---
title: "Класс SVGSetElementBuilder"
second_title: "Aspose.SVG для .NET справочник API"
description: "Класс Aspose.Svg.Builder.SVGSetElementBuilder. Класс‑строитель для создания элемента SVG set. Элемент set используется для определения простой анимации, в которой значение одного атрибута меняется в течение определённого времени. Этот класс предоставляет методы для установки различных атрибутов, специфичных для элемента set, таких как целевой атрибут и значение для установки."
type: docs
weight: 1610
url: /ru/net/aspose.svg.builder/svgsetelementbuilder/
---
## SVGSetElementBuilder class

Класс‑строитель для создания SVG‑элемента 'set'. Элемент 'set' используется для определения простой анимации, при которой значение одного атрибута меняется в течение определённого времени. Этот класс предоставляет методы для установки различных атрибутов, специфичных для элемента 'set', таких как целевой атрибут и устанавливаемое значение.

```csharp
public class SVGSetElementBuilder : SVGElementBuilder<SVGSetElement>, 
    IAnimationEventAttributeSetter, IAnimationTargetAttributeSetter, 
    IAnimationTargetElementAttributeSetter, IAnimationTimingAttributeSetter, 
    IConditionalProcessingAttributeSetter, ICoreAttributeSetter, IDescriptiveElementBuilder, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SVGSetElementBuilder](svgsetelementbuilder/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Методы

| Имя | Описание |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGSetElement](../../aspose.svg/svgsetelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [To](../../aspose.svg.builder/svgsetelementbuilder/to/)(*string*) | Устанавливает атрибут 'to' элемента SVG 'set', указывая окончательное значение атрибута, которое будет изменено во время анимации. |

### См. также

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGSetElement](../../aspose.svg/svgsetelement/)
* interface [IAnimationEventAttributeSetter](../ianimationeventattributesetter/)
* interface [IAnimationTargetAttributeSetter](../ianimationtargetattributesetter/)
* interface [IAnimationTargetElementAttributeSetter](../ianimationtargetelementattributesetter/)
* interface [IAnimationTimingAttributeSetter](../ianimationtimingattributesetter/)
* interface [IConditionalProcessingAttributeSetter](../iconditionalprocessingattributesetter/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDescriptiveElementBuilder](../idescriptiveelementbuilder/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
