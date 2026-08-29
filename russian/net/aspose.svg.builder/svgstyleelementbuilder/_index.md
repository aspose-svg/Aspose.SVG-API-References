---
title: "SVGStyleElementBuilder Класс"
second_title: "Aspose.SVG для .NET справочник API"
description: "Aspose.Svg.Builder.SVGStyleElementBuilder класс. Класс‑строитель для создания SVG‑элемента style. Этот класс облегчает создание и настройку SVG‑элемента style с правилами CSS."
type: docs
weight: 1630
url: /ru/net/aspose.svg.builder/svgstyleelementbuilder/
---
## SVGStyleElementBuilder class

Класс‑строитель для создания SVG‑элемента 'style'. Этот класс упрощает создание и настройку SVG‑элемента стиля с правилами CSS.

```csharp
public class SVGStyleElementBuilder : SVGElementBuilder<SVGStyleElement>, ICoreAttributeSetter, 
    IDocumentElementEventAttributeSetter, IGlobalEventAttributeSetter
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SVGStyleElementBuilder](svgstyleelementbuilder/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } |  |

## Методы

| Имя | Описание |
| --- | --- |
| [AddComment](../../aspose.svg.builder/svgstyleelementbuilder/addcomment/)(*string*) | Добавляет комментарий к содержимому стиля. |
| [AddRule](../../aspose.svg.builder/svgstyleelementbuilder/addrule/#addrule)(*string, Action&lt;RuleBuilder&gt;*) | Добавляет правило CSS к элементу style, используя RuleBuilder. |
| [AddRule](../../aspose.svg.builder/svgstyleelementbuilder/addrule/#addrule_1)(*string, string*) | Добавляет правило CSS к элементу style. |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) |  |
| override [Build](../../aspose.svg.builder/svgstyleelementbuilder/build/#build)(*[Document](../../aspose.svg.dom/document/)*) | Создаёт SVG‑элемент style с накопленными правилами CSS и добавляет его в указанный документ. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/)(*[SVGStyleElement](../../aspose.svg/svgstyleelement/)*) |  |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) |  |
| [Media](../../aspose.svg.builder/svgstyleelementbuilder/media/)(*string*) | Устанавливает атрибут 'media' SVG‑элемента 'style'. Этот атрибут указывает носитель, для которого предназначены стили, позволяя делать стили условными в зависимости от типа носителя. |
| [Title](../../aspose.svg.builder/svgstyleelementbuilder/title/)(*string*) | Устанавливает атрибут 'title' SVG‑элемента 'style'. Этот атрибут предоставляет рекомендованный заголовок для элемента style, что может быть полезно для доступности и текста всплывающих подсказок. |
| [Type](../../aspose.svg.builder/svgstyleelementbuilder/type/)(*string*) | Устанавливает атрибут 'type' SVG‑элемента 'style'. Этот атрибут указывает язык таблицы стилей содержимого элемента. |

### См. также

* class [SVGElementBuilder&lt;T&gt;](../svgelementbuilder-1/)
* class [SVGStyleElement](../../aspose.svg/svgstyleelement/)
* interface [ICoreAttributeSetter](../icoreattributesetter/)
* interface [IDocumentElementEventAttributeSetter](../idocumentelementeventattributesetter/)
* interface [IGlobalEventAttributeSetter](../iglobaleventattributesetter/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
