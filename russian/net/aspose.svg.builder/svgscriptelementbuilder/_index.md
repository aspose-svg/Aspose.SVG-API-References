---
title: "Класс SVGScriptElementBuilder"
second_title: "Aspose.SVG для .NET справочник API"
description: "Класс Aspose.Svg.Builder.SVGScriptElementBuilder. Класс‑строитель для создания элемента script SVG. Элемент script используется для встраивания или ссылки на исполняемые скрипты внутри SVG‑документов. Этот класс предоставляет методы для установки различных атрибутов, специфичных для элемента script, таких как type, source и настройки cross-origin."
type: docs
weight: 1600
url: /ru/net/aspose.svg.builder/svgscriptelementbuilder/
---
## SVGScriptElementBuilder class

Класс‑строитель для создания SVG‑элемента 'script'. Элемент 'script' используется для внедрения или ссылки на исполняемые скрипты в SVG‑документах. Этот класс предоставляет методы для установки различных атрибутов, специфичных для элемента 'script', таких как тип, источник и настройки cross-origin.

```csharp
public class SVGScriptElementBuilder : SVGElementBuilder<SVGScriptElement>, ICoreAttributeSetter, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SVGScriptElementBuilder](svgscriptelementbuilder/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Методы

| Имя | Описание |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGScriptElement](../../aspose.svg/svgscriptelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Crossorigin](../../aspose.svg.builder/svgscriptelementbuilder/crossorigin/)(*string*) | Устанавливает атрибут 'crossorigin' элемента SVG 'script', указывая настройки CORS для внешнего скрипта. |
| [Href](../../aspose.svg.builder/svgscriptelementbuilder/href/)(*string*) | Устанавливает атрибут 'href' элемента SVG 'script', указывая URL внешнего файла скрипта. |
| [Type](../../aspose.svg.builder/svgscriptelementbuilder/type/)(*string*) | Устанавливает атрибут 'type' элемента SVG 'script', указывая тип языка скриптов (например, "text/javascript"). |

### См. также

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGScriptElement](../../aspose.svg/svgscriptelement/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
