---
title: "OneOf-3.Match"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "OneOf Match-methode. Voert een van de opgegeven functies uit op basis van het onderliggende type van de waarde"
type: docs
weight: 20
url: /nl/net/aspose.svg.builder/oneof-3/match/
---
## OneOf<T1,T2,T3>.Match<TResult> method

Voert een van de opgegeven functies uit op basis van het onderliggende type van de waarde.

```csharp
public TResult Match<TResult>(Func<T1, TResult> func1, Func<T2, TResult> func2, 
    Func<T3, TResult> func3)
```

| Parameter | Beschrijving |
| --- | --- |
| TResult | Het retourtype van de functies. |
| func1 | De functie die moet worden uitgevoerd als de waarde van type T1 is. |
| func2 | De functie die moet worden uitgevoerd als de waarde van type T2 is. |
| func3 | De functie die moet worden uitgevoerd als de waarde van type T3 is. |

### Retourwaarde

Het resultaat van de uitgevoerde functie.

### Zie ook

* class [OneOf&lt;T1,T2,T3&gt;](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
