---
title: "Enumeración FillRule"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Enumeración Aspose.Svg.Builder.FillRule. Especifica la regla para determinar qué partes de una forma están dentro o fuera en los gráficos SVG."
type: docs
weight: 270
url: /es/net/aspose.svg.builder/fillrule/
---
## FillRule enumeration

Especifica la regla para determinar qué partes de una forma están dentro o fuera en gráficos SVG.

```csharp
public enum FillRule
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Nonzero | `0` | La regla de enrollamiento no nula: Determina la "interioridad" de un punto en la forma dibujando un rayo desde ese punto hasta el infinito en cualquier dirección y contando el número de segmentos de ruta de la forma dada que el rayo cruza. Si este número es impar, el punto está dentro; si es par, el punto está fuera. |
| Evenodd | `1` | La regla de enrollamiento par-impar: Determina la "interioridad" de un punto en la forma dibujando un rayo desde ese punto hasta el infinito en cualquier dirección y contando el número de segmentos de ruta de la forma dada que el rayo cruza. Si este número es par, el punto está fuera; si es impar, el punto está dentro. |

### Ver también

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
