---
title: "Класс SVGListBaseT"
second_title: "Aspose.SVG для .NET справочник API"
description: "Класс Aspose.Svg.Collections.SVGListBase1T. Этот интерфейс определяет базовый список всех SVG‑списков"
type: docs
weight: 2040
url: /ru/net/aspose.svg.collections/svglistbase-1/
---
## SVGListBase<T> class

Этот интерфейс определяет базовый список всех списков SVG.

```csharp
public abstract class SVGListBase<T> : SVGValueType, IEnumerable<T>
```

| Параметр | Описание |
| --- | --- |
| T | Тип элемента, хранящегося в списке. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Item](../../aspose.svg.collections/svglistbase-1/item/) { get; set; } | Возвращает элемент с индексом index в списке. |
| [Length](../../aspose.svg.collections/svglistbase-1/length/) { get; } | Количество элементов в списке. |
| [NumberOfItems](../../aspose.svg.collections/svglistbase-1/numberofitems/) { get; } | Количество элементов в списке. |

## Методы

| Имя | Описание |
| --- | --- |
| [AppendItem](../../aspose.svg.collections/svglistbase-1/appenditem/)(*T*) | Вставляет новый элемент в конец списка. |
| [Clear](../../aspose.svg.collections/svglistbase-1/clear/)() | Очищает все текущие элементы из списка, в результате получая пустой список. |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | Освобождает неуправляемые и — при необходимости — управляемые ресурсы. |
| [GetEnumerator](../../aspose.svg.collections/svglistbase-1/getenumerator/)() | Получает перечислитель. |
| [GetItem](../../aspose.svg.collections/svglistbase-1/getitem/)(*ulong*) | Возвращает указанный элемент из списка. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Этот метод используется для получения типа ECMAScript‑объекта. |
| [Initialize](../../aspose.svg.collections/svglistbase-1/initialize/)(*T*) | Очищает все текущие элементы из списка и переинициализирует список, чтобы содержать единственный элемент, указанный параметром. |
| [InsertItemBefore](../../aspose.svg.collections/svglistbase-1/insertitembefore/)(*T, ulong*) | Вставляет новый элемент в список в указанную позицию. Первый элемент имеет номер 0. |
| [RemoveItem](../../aspose.svg.collections/svglistbase-1/removeitem/)(*ulong*) | Удаляет существующий элемент из списка. |
| [ReplaceItem](../../aspose.svg.collections/svglistbase-1/replaceitem/)(*T, ulong*) | Заменяет существующий элемент в списке новым элементом. |

### См. также

* class [SVGValueType](../../aspose.svg.datatypes/svgvaluetype/)
* namespace [Aspose.Svg.Collections](../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../)
