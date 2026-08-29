---
title: "SVGElementBuilderT Class"
second_title: "Aspose.SVG для .NET справочник API"
description: "Aspose.Svg.Builder.SVGElementBuilder1T class. Представляет базовый класс для построения SVG‑элементов типа T"
type: docs
weight: 1160
url: /ru/net/aspose.svg.builder/svgelementbuilder-1/
---
## SVGElementBuilder<T> class

Представляет базовый класс для построения SVG‑элементов типа *T*.

```csharp
public abstract class SVGElementBuilder<T> : ISVGElementBuilder
    where T : SVGElement
```

| Параметр | Описание |
| --- | --- |
| T | Тип SVG‑элемента, который этот билдер отвечает за создание. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Configurations](../../aspose.svg.builder/svgelementbuilder-1/configurations/) { get; } | Получает список конфигураций, которые будут применены к SVG‑элементу. |

## Методы

| Имя | Описание |
| --- | --- |
| [Attribute](../../aspose.svg.builder/svgelementbuilder-1/attribute/)(*string, string*) | Добавляет конфигурацию атрибута к SVG‑элементу. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/#build)(*[Document](../../aspose.svg.dom/document/)*) | Создаёт SVG‑элемент и применяет к нему все конфигурации. |
| virtual [Build](../../aspose.svg.builder/svgelementbuilder-1/build/#build_1)(*T*) | Применяет конфигурации к существующему SVG‑элементу. |
| [BuildElement](../../aspose.svg.builder/svgelementbuilder-1/buildelement/)(*[Document](../../aspose.svg.dom/document/)*) | Создает элемент SVG как общий SVGElement. |

### См. также

* interface [ISVGElementBuilder](../isvgelementbuilder/)
* class [SVGElement](../../aspose.svg/svgelement/)
* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
