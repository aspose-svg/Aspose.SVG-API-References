---
title: "Класс SVGStopElementBuilder"
second_title: "Aspose.SVG для .NET справочник API"
description: "Класс Aspose.Svg.Builder.SVGStopElementBuilder. Класс‑строитель для создания SVG‑элемента stop. Элемент stop используется в определении градиента, линейного или радиального, для задания цветовых остановок. Этот класс предоставляет методы для установки различных атрибутов, специфичных для элемента stop, таких как offset и color."
type: docs
weight: 1620
url: /ru/net/aspose.svg.builder/svgstopelementbuilder/
---
## SVGStopElementBuilder class

Класс‑строитель для создания SVG‑элемента 'stop'. Элемент 'stop' используется в определении градиента (линейного или радиального) для задания цветовых остановок. Этот класс предоставляет методы для установки различных атрибутов, специфичных для элемента 'stop', таких как смещение и цвет.

```csharp
public class SVGStopElementBuilder : SVGElementBuilder<SVGStopElement>, 
    IBaseAnimationElementBuilder, ICoreAttributeSetter, IDocumentElementEventAttributeSetter, 
    IGlobalEventAttributeSetter, IPresentationAttributeSetter
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SVGStopElementBuilder](svgstopelementbuilder/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Методы

| Имя | Описание |
| --- | --- |
| [AddScript](../../aspose.svg.builder/svgstopelementbuilder/addscript/)(*Action&lt;SVGScriptElementBuilder&gt;*) | Добавляет конфигурацию скрипта к SVG‑элементу 'stop'. |
| [AddStyle](../../aspose.svg.builder/svgstopelementbuilder/addstyle/)(*Action&lt;SVGStyleElementBuilder&gt;*) | Добавляет конфигурацию стиля к SVG‑элементу 'stop'. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGStopElement](../../aspose.svg/svgstopelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Offset](../../aspose.svg.builder/svgstopelementbuilder/offset/)(*double, [StopUnitType](../stopunittype/)*) | Устанавливает атрибут 'offset' SVG‑элемента 'stop', указывая положение цветовой остановки внутри градиента. |

### См. также

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGStopElement](../../aspose.svg/svgstopelement/)
* interface [IBaseAnimationElementBuilder](../ibaseanimationelementbuilder/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* interface [IPresentationAttributeSetter](../ipresentationattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
