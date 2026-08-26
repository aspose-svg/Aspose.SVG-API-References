---
title: "OneOf-2.Match"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "OneOf Match‑Methode. Führt eine der bereitgestellten Funktionen aus, basierend auf dem zugrunde liegenden Typ des Werts."
type: docs
weight: 20
url: /de/net/aspose.svg.builder/oneof-2/match/
---
## OneOf<T1,T2>.Match<TResult> method

Führt eine der bereitgestellten Funktionen aus, basierend auf dem zugrunde liegenden Typ des Werts.

```csharp
public TResult Match<TResult>(Func<T1, TResult> func1, Func<T2, TResult> func2)
```

| Parameter | Beschreibung |
| --- | --- |
| TResult | Der Rückgabetyp der Funktionen. |
| func1 | Die Funktion, die ausgeführt wird, wenn der Wert vom Typ T1 ist. |
| func2 | Die Funktion, die ausgeführt werden soll, wenn der Wert vom Typ T2 ist. |

### Rückgabewert

Das Ergebnis der ausgeführten Funktion.

### Siehe auch

* class [OneOf&lt;T1,T2&gt;](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
