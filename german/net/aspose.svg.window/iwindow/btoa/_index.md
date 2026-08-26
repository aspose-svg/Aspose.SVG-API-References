---
title: "IWindow.Btoa"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "IWindow Btoa Methode. Nimmt die Eingabedaten in Form einer Unicode-Zeichenkette, die nur Zeichen im Bereich U0000 bis U00FF enthält, wobei jedes Zeichen ein Binärbyte mit den Werten 0x00 bis 0xFF darstellt, und wandelt sie in ihre Base64-Darstellung um, die zurückgegeben wird."
type: docs
weight: 130
url: /de/net/aspose.svg.window/iwindow/btoa/
---
## IWindow.Btoa method

Nimmt die Eingabedaten in Form eines Unicode‑Strings, der nur Zeichen im Bereich U+0000 bis U+00FF enthält, wobei jedes Zeichen ein Binärbyte mit den Werten 0x00 bis 0xFF darstellt, und wandelt ihn in seine base64‑Darstellung um, die zurückgegeben wird.

```csharp
public string Btoa(string data)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | String | Die Unicode-Zeichenkette, die nur Zeichen im Bereich U+0000 bis U+00FF enthält. |

### Rückgabewert

Die Base64-Zeichenkette.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Wirft eine "InvalidCharacterError" DOMException, wenn die Eingabezeichenkette Zeichen außerhalb des zulässigen Bereichs enthält. |

### Siehe auch

* interface [IWindow](../)
* namespace [Aspose.Svg.Window](../../../aspose.svg.window/)
* assembly [Aspose.SVG](../../../)
