---
title: "OneOf-2.Match"
second_title: "Aspose.SVG för .NET API-referens"
description: "OneOf Match-metod. Utför en av de angivna funktionerna baserat på värdets underliggande typ"
type: docs
weight: 20
url: /sv/net/aspose.svg.builder/oneof-2/match/
---
## OneOf<T1,T2>.Match<TResult> method

Utför en av de angivna funktionerna baserat på den underliggande typen av värdet.

```csharp
public TResult Match<TResult>(Func<T1, TResult> func1, Func<T2, TResult> func2)
```

| Parameter | Beskrivning |
| --- | --- |
| TResult | Returtyp för funktionerna. |
| func1 | Funktionen som ska köras om värdet är av typen T1. |
| func2 | Funktionen som ska köras om värdet är av typen T2. |

### Returvärde

Resultatet av den körda funktionen.

### Se även

* class [OneOf&lt;T1,T2&gt;](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
