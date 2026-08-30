---
title: "OneOf-3.Match"
second_title: "Aspose.SVG för .NET API-referens"
description: "OneOf Match-metod. Utför en av de angivna funktionerna baserat på värdets underliggande typ"
type: docs
weight: 20
url: /sv/net/aspose.svg.builder/oneof-3/match/
---
## OneOf<T1,T2,T3>.Match<TResult> method

Utför en av de angivna funktionerna baserat på den underliggande typen av värdet.

```csharp
public TResult Match<TResult>(Func<T1, TResult> func1, Func<T2, TResult> func2, 
    Func<T3, TResult> func3)
```

| Parameter | Beskrivning |
| --- | --- |
| TResult | Returtyp för funktionerna. |
| func1 | Funktionen som ska köras om värdet är av typen T1. |
| func2 | Funktionen som ska köras om värdet är av typen T2. |
| func3 | Funktionen som ska köras om värdet är av typen T3. |

### Returvärde

Resultatet av den körda funktionen.

### Se även

* class [OneOf&lt;T1,T2,T3&gt;](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
