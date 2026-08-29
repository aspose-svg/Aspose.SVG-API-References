---
title: "IWindow.Btoa"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "IWindow Btoa methode. Neemt de invoergegevens in de vorm van een Unicode‑string die alleen tekens bevat in het bereik U0000 tot U00FF, elk een binair byte met waarden 0x00 tot 0xFF representerend, en zet deze om naar de base64‑representatie die wordt geretourneerd."
type: docs
weight: 130
url: /nl/net/aspose.svg.window/iwindow/btoa/
---
## IWindow.Btoa method

Neemt de invoergegevens, in de vorm van een Unicode‑string die alleen tekens bevat in het bereik U+0000 tot U+00FF, elk een binair byte met waarden 0x00 tot 0xFF respectievelijk, en zet deze om naar de base64‑representatie, die wordt geretourneerd.

```csharp
public string Btoa(string data)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | String | De Unicode‑string die alleen tekens bevat in het bereik U+0000 tot U+00FF. |

### Retourwaarde

De base64‑string.

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Gooit een "InvalidCharacterError" DOMException‑exception als de invoerstring tekens buiten het bereik bevat. |

### Zie ook

* interface [IWindow](../)
* namespace [Aspose.Svg.Window](../../../aspose.svg.window/)
* assembly [Aspose.SVG](../../../)
