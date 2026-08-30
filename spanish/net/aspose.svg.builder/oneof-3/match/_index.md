---
title: "OneOf-3.Match"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método Match de OneOf. Ejecuta una de las funciones proporcionadas según el tipo subyacente del valor"
type: docs
weight: 20
url: /es/net/aspose.svg.builder/oneof-3/match/
---
## OneOf<T1,T2,T3>.Match<TResult> method

Ejecuta una de las funciones proporcionadas según el tipo subyacente del valor.

```csharp
public TResult Match<TResult>(Func<T1, TResult> func1, Func<T2, TResult> func2, 
    Func<T3, TResult> func3)
```

| Parámetro | Descripción |
| --- | --- |
| TResult | El tipo de retorno de las funciones. |
| func1 | La función a ejecutar si el valor es del tipo T1. |
| func2 | La función a ejecutar si el valor es del tipo T2. |
| func3 | La función a ejecutar si el valor es del tipo T3. |

### Valor de retorno

El resultado de la función ejecutada.

### Ver también

* class [OneOf&lt;T1,T2,T3&gt;](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
