---
title: "IWindow.Btoa"
second_title: "Aspose.SVG för .NET API-referens"
description: "IWindow Btoa-metod. Tar indata i form av en Unicode-sträng som endast innehåller tecken i intervallet U0000 till U00FF, där varje tecken representerar en binär byte med värden 0x00 till 0xFF respektive, och konverterar den till dess base64-representation som den returnerar."
type: docs
weight: 130
url: /sv/net/aspose.svg.window/iwindow/btoa/
---
## IWindow.Btoa method

Tar emot indata i form av en Unicode-sträng som endast innehåller tecken i intervallet U+0000 till U+00FF, där varje tecken representerar en binär byte med värden 0x00 till 0xFF respektive, och konverterar den till dess base64-representation, som den returnerar.

```csharp
public string Btoa(string data)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | String | Unicode-strängen som endast innehåller tecken i intervallet U+0000 till U+00FF. |

### Returvärde

Base64-strängen.

### Undantag

| undantag | villkor |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Kastar ett "InvalidCharacterError" DOMException-fel om inmatningssträngen innehåller tecken utanför intervallet. |

### Se även

* interface [IWindow](../)
* namespace [Aspose.Svg.Window](../../../aspose.svg.window/)
* assembly [Aspose.SVG](../../../)
