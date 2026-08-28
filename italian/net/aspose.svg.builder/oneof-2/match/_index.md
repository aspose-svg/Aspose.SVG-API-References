---
title: "OneOf-2.Match"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo Match di OneOf. Esegue una delle funzioni fornite in base al tipo sottostante del valore."
type: docs
weight: 20
url: /it/net/aspose.svg.builder/oneof-2/match/
---
## OneOf<T1,T2>.Match<TResult> method

Esegue una delle funzioni fornite in base al tipo sottostante del valore.

```csharp
public TResult Match<TResult>(Func<T1, TResult> func1, Func<T2, TResult> func2)
```

| Parametro | Descrizione |
| --- | --- |
| TResult | Il tipo di ritorno delle funzioni. |
| func1 | La funzione da eseguire se il valore è di tipo T1. |
| func2 | La funzione da eseguire se il valore è di tipo T2. |

### Valore di ritorno

Il risultato della funzione eseguita.

### Vedi anche

* class [OneOf&lt;T1,T2&gt;](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
