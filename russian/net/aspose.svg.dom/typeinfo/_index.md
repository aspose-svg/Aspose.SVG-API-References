---
title: "Класс TypeInfo"
second_title: "Aspose.SVG для .NET справочник API"
description: "Aspose.Svg.Dom.TypeInfo class. TypeInfo представляет тип, на который ссылаются узлы Element или Attr, указанные в схемах, связанных с документом."
type: docs
weight: 3280
url: /ru/net/aspose.svg.dom/typeinfo/
---
## TypeInfo class

TypeInfo представляет тип, на который ссылаются узлы Element или Attr, указанный в схемах, связанных с документом.

```csharp
public class TypeInfo : DOMObject
```

## Свойства

| Имя | Описание |
| --- | --- |
| [TypeName](../../aspose.svg.dom/typeinfo/typename/) { get; } | Имя типа, объявленного для связанного элемента или атрибута, или null, если неизвестно. |
| [TypeNamespace](../../aspose.svg.dom/typeinfo/typenamespace/) { get; } | Получает пространство имён типа. Пространство имён типа, объявленного для связанного элемента или атрибута, или null, если элемент не имеет объявления или если информация о пространстве имён недоступна. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Этот метод используется для получения типа ECMAScript‑объекта. |
| [IsDerivedFrom](../../aspose.svg.dom/typeinfo/isderivedfrom/)(*string, string, ulong*) | Этот метод возвращает, существует ли наследование между определением ссылочного типа, т.е. TypeInfo, на котором вызывается метод, и другим определением типа, т.е. переданным в параметрах. |

## Поля

| Имя | Описание |
| --- | --- |
| const [DERIVATION_EXTENSION](../../aspose.svg.dom/typeinfo/derivation_extension/) | Если схема документа является XML Schema [XML Schema Part 1], эта константа представляет наследование посредством расширения. |
| const [DERIVATION_LIST](../../aspose.svg.dom/typeinfo/derivation_list/) | Если схема документа является XML Schema [XML Schema Part 1], эта константа представляет список. |
| const [DERIVATION_RESTRICTION](../../aspose.svg.dom/typeinfo/derivation_restriction/) | Если схема документа является XML Schema [XML Schema Part 1], эта константа представляет наследование посредством ограничения, если задействованы сложные типы, или ограничение, если задействованы простые типы. |
| const [DERIVATION_UNION](../../aspose.svg.dom/typeinfo/derivation_union/) | Если схема документа является XML Schema [XML Schema Part 1], эта константа представляет объединение, если задействованы простые типы. |

### См. также

* class [DOMObject](../domobject/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
