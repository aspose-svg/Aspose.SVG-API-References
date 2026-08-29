---
title: "Интерфейс IUrlSearchParams"
second_title: "Aspose.SVG для .NET справочник API"
description: "Интерфейс Aspose.Svg.IUrlSearchParams. Предоставляет методы для работы со строкой запроса URL"
type: docs
weight: 4140
url: /ru/net/aspose.svg/iurlsearchparams/
---
## IUrlSearchParams interface

Предоставляет методы для работы со строкой запроса URL.

```csharp
public interface IUrlSearchParams : IEnumerable<string[]>
```

## Методы

| Имя | Описание |
| --- | --- |
| [Append](../../aspose.svg/iurlsearchparams/append/)(*string, string*) | Добавляет новую пару имя‑значение, где имя — `name`, а значение — `value`. |
| [Delete](../../aspose.svg/iurlsearchparams/delete/)(*string*) | Удаляет все пары имя‑значение, у которых имя равно `name`. |
| [Get](../../aspose.svg/iurlsearchparams/get/)(*string*) | Возвращает значение первой пары имя‑значение, у которой имя равно `name`. |
| [GetAll](../../aspose.svg/iurlsearchparams/getall/)(*string*) | Возвращает все значения, имя которых `name`. |
| [Has](../../aspose.svg/iurlsearchparams/has/)(*string*) | Проверяет, существует ли в списке пара имя‑значение, имя которой `name`. |
| [Set](../../aspose.svg/iurlsearchparams/set/)(*string, string*) | Устанавливает значение первой найденной пары имя‑значение в указанное значение и удаляет остальные. Если пары имя‑значение с указанным именем не найдены, в список будет добавлена новая. |
| [Sort](../../aspose.svg/iurlsearchparams/sort/)() | Сортирует все пары имя‑значение, если они есть, по их именам. |

### См. также

* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)
