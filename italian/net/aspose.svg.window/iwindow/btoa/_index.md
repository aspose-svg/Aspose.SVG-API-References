---
title: "IWindow.Btoa"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo Btoa di IWindow. Accetta i dati di input sotto forma di stringa Unicode contenente solo caratteri nell'intervallo U0000‑U00FF, ciascuno rappresentante un byte binario con valori da 0x00 a 0xFF rispettivamente, e lo converte nella sua rappresentazione base64 che restituisce"
type: docs
weight: 130
url: /it/net/aspose.svg.window/iwindow/btoa/
---
## IWindow.Btoa method

Accetta i dati di input, sotto forma di stringa Unicode contenente solo caratteri nell'intervallo U+0000‑U+00FF, ciascuno rappresentante un byte binario con valori da 0x00 a 0xFF rispettivamente, e li converte nella sua rappresentazione base64, che restituisce.

```csharp
public string Btoa(string data)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | String | La stringa Unicode contenente solo caratteri nell'intervallo U+0000‑U+00FF. |

### Valore di ritorno

La stringa base64.

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Genera un'eccezione DOMException "InvalidCharacterError" se la stringa di input contiene caratteri fuori dall'intervallo. |

### Vedi anche

* interface [IWindow](../)
* namespace [Aspose.Svg.Window](../../../aspose.svg.window/)
* assembly [Aspose.SVG](../../../)
