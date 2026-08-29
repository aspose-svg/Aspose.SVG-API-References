---
title: "ComponentTransferType Перечисление"
second_title: "Aspose.SVG для .NET справочник API"
description: "Aspose.Svg.Builder.ComponentTransferType enum. Определяет тип функции передачи компонента, применяемой в примитиве фильтра FeComponentTransfer SVG"
type: docs
weight: 170
url: /ru/net/aspose.svg.builder/componenttransfertype/
---
## ComponentTransferType enumeration

Указывает тип функции передачи компонентов, применяемой в примитиве фильтра FeComponentTransfer SVG.

```csharp
public enum ComponentTransferType
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Identity | `0` | Представляет отсутствие изменений во входном графическом объекте. Это тип по умолчанию. |
| Table | `1` | Использует таблицу поиска для определения функции внутри фильтра. |
| Discrete | `2` | Использует набор дискретных значений для определения функции в фильтре. |
| Linear | `3` | Определяет линейное преобразование компонента внутри фильтра. |
| Gamma | `4` | Определяет преобразование гамма‑коррекции в фильтре. |

## Замечания

Элемент примитива фильтра FeComponentTransfer позволяет индивидуально манипулировать цветовыми компонентами (RGB и альфа) графических элементов, используя различные типы функций переноса. Каждый тип определяет отдельный метод вычисления преобразования цветовых компонентов внутри фильтра.

### См. также

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
