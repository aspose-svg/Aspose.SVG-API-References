---
title: "IWindow.Atob"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "IWindow Atob-Methode. Nimmt die Eingabedaten in Form eines Unicode-Strings, der base64-codierte Binärdaten enthält, dekodiert sie und gibt einen String zurück, der aus Zeichen im Bereich U0000 bis U00FF besteht, wobei jedes Zeichen ein Binärbyte mit den Werten 0x00 bis 0xFF darstellt, das den jeweiligen Binärdaten entspricht."
type: docs
weight: 120
url: /de/net/aspose.svg.window/iwindow/atob/
---
## IWindow.Atob method

Nimmt die Eingabedaten in Form eines Unicode‑Strings, der base64‑kodierte Binärdaten enthält, dekodiert sie und gibt einen String zurück, der aus Zeichen im Bereich U+0000 bis U+00FF besteht, wobei jedes Zeichen ein Binärbyte mit den Werten 0x00 bis 0xFF darstellt, entsprechend den Binärdaten.

```csharp
public string Atob(string data)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | String | Der Unicode-String, der base64-codierte Binärdaten enthält |

### Rückgabewert

Der String, der aus Zeichen im Bereich U+0000 bis U+00FF besteht

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Wirft eine \"InvalidCharacterError\" DOMException, wenn der Eingabestring keine gültigen Base64-Daten enthält. |

### Siehe auch

* interface [IWindow](../)
* namespace [Aspose.Svg.Window](../../../aspose.svg.window/)
* assembly [Aspose.SVG](../../../)
