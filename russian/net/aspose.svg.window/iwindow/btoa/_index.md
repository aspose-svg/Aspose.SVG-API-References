---
title: "IWindow.Btoa"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод IWindow Btoa. Принимает входные данные в виде Unicode‑строки, содержащей только символы в диапазоне U0000–U00FF, каждый из которых представляет бинарный байт со значениями 0x00–0xFF, и преобразует её в её base64‑представление, которое возвращает."
type: docs
weight: 130
url: /ru/net/aspose.svg.window/iwindow/btoa/
---
## IWindow.Btoa method

Принимает входные данные в виде строки Unicode, содержащей только символы в диапазоне U+0000–U+00FF, каждый из которых представляет бинарный байт со значениями 0x00–0xFF соответственно, и преобразует её в представление base64, которое возвращает.

```csharp
public string Btoa(string data)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | String | Unicode‑строка, содержащая только символы в диапазоне U+0000–U+00FF. |

### Возвращаемое значение

Base64‑строка.

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Выбрасывает исключение DOMException "InvalidCharacterError", если входная строка содержит символы вне диапазона. |

### См. также

* interface [IWindow](../)
* namespace [Aspose.Svg.Window](../../../aspose.svg.window/)
* assembly [Aspose.SVG](../../../)
