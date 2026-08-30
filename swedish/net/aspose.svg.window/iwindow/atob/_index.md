---
title: "IWindow.Atob"
second_title: "Aspose.SVG för .NET API-referens"
description: "IWindow Atob method. Tar indata i form av en Unicode-sträng som innehåller base64-kodad binär data, avkodar den och returnerar en sträng bestående av tecken i intervallet U0000 till U00FF, där varje tecken representerar en binär byte med värden 0x00 till 0xFF som motsvarar den binära datan."
type: docs
weight: 120
url: /sv/net/aspose.svg.window/iwindow/atob/
---
## IWindow.Atob method

Tar emot indata i form av en Unicode-sträng som innehåller base64-kodad binär data, avkodar den och returnerar en sträng bestående av tecken i intervallet U+0000 till U+00FF, där varje tecken representerar en binär byte med värden 0x00 till 0xFF respektive, motsvarande den binära datan.

```csharp
public string Atob(string data)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | String | Unicode-strängen som innehåller base64-kodad binär data |

### Returvärde

Strängen som består av tecken i intervallet U+0000 till U+00FF

### Undantag

| undantag | villkor |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Kastar ett "InvalidCharacterError" DOMException om inmatningssträngen inte är giltig base64-data. |

### Se även

* interface [IWindow](../)
* namespace [Aspose.Svg.Window](../../../aspose.svg.window/)
* assembly [Aspose.SVG](../../../)
