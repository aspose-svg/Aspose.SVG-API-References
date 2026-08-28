---
title: "IWindow.Atob"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo IWindow Atob. Prende i dati di input sotto forma di una stringa Unicode contenente dati binari codificati in base64, li decodifica e restituisce una stringa composta da caratteri nell'intervallo U0000 a U00FF, ciascuno rappresentante un byte binario con valori da 0x00 a 0xFF corrispondenti a quei dati binari."
type: docs
weight: 120
url: /it/net/aspose.svg.window/iwindow/atob/
---
## IWindow.Atob method

Prende i dati di input, sotto forma di una stringa Unicode contenente dati binari codificati in base64, li decodifica e restituisce una stringa composta da caratteri nell'intervallo U+0000 a U+00FF, ciascuno rappresentante un byte binario con valori da 0x00 a 0xFF corrispondenti a quei dati binari.

```csharp
public string Atob(string data)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | String | La stringa Unicode contenente dati binari codificati in base64 |

### Valore di ritorno

La stringa composta da caratteri nell'intervallo U+0000 a U+00FF

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Genera un'eccezione DOMException "InvalidCharacterError" se la stringa di input non è un dato base64 valido. |

### Vedi anche

* interface [IWindow](../)
* namespace [Aspose.Svg.Window](../../../aspose.svg.window/)
* assembly [Aspose.SVG](../../../)
