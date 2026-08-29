---
title: "Интерфейс IWindowTimers"
second_title: "Aspose.SVG для .NET справочник API"
description: "Интерфейс Aspose.Svg.Window.IWindowTimers. Позволяет разработчикам планировать обратные вызовы, основанные на таймерах"
type: docs
weight: 5940
url: /ru/net/aspose.svg.window/iwindowtimers/
---
## IWindowTimers interface

Позволяет авторам планировать обратные вызовы, основанные на таймерах.

```csharp
public interface IWindowTimers
```

## Методы

| Имя | Описание |
| --- | --- |
| [ClearInterval](../../aspose.svg.window/iwindowtimers/clearinterval/)(*int*) | Отменяет таймаут, установленный с помощью setInterval(), идентифицированный дескриптором handle |
| [ClearTimeout](../../aspose.svg.window/iwindowtimers/cleartimeout/)(*int*) | Отменяет таймаут, установленный с помощью setTimeout(), идентифицированный дескриптором handle. |
| [SetInterval](../../aspose.svg.window/iwindowtimers/setinterval/)(*object, int, params object[]*) | Запускает таймаут, вызывающий обработчик каждые timeout миллисекунд. Все аргументы передаются напрямую обработчику. |
| [SetTimeout](../../aspose.svg.window/iwindowtimers/settimeout/)(*object, int, params object[]*) | Запускает таймаут, вызывающий обработчик через timeout миллисекунд. Все аргументы передаются напрямую обработчику. |

### См. также

* namespace [Aspose.Svg.Window](../../aspose.svg.window/)
* assembly [Aspose.SVG](../../)
