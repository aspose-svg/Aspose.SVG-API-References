---
title: "OneOf-2.Match"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método Match de OneOf. Ejecuta una de las funciones proporcionadas según el tipo subyacente del valor"
type: docs
weight: 20
url: /es/net/aspose.svg.builder/oneof-2/match/
---
## OneOf<T1,T2>.Match<TResult> method

Ejecuta una de las funciones proporcionadas según el tipo subyacente del valor.

```csharp
public TResult Match<TResult>(Func<T1, TResult> func1, Func<T2, TResult> func2)
```

| Parámetro | Descripción |
| --- | --- |
| TResult | El tipo de retorno de las funciones. |
| func1 | La función a ejecutar si el valor es del tipo T1. |
| func2 | La función a ejecutar si el valor es del tipo T2. |

### Valor de retorno

El resultado de la función ejecutada.

### Ver también

* class [OneOf&lt;T1,T2&gt;](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
