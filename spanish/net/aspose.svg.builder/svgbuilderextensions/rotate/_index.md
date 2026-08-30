---
title: "SVGBuilderExtensions.Rotate"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método Rotate de SVGBuilderExtensions. Establece ángulos de rotación para caracteres individuales o segmentos del contenido de texto"
type: docs
weight: 2000
url: /es/net/aspose.svg.builder/svgbuilderextensions/rotate/
---
## Rotate<TBuilder>(*this TBuilder, params double[]*) {#rotate_1}

Establece ángulos de rotación para caracteres individuales o segmentos del contenido de texto.

```csharp
public static TBuilder Rotate<TBuilder>(this TBuilder builder, params double[] values)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | El constructor de elementos SVG. |
| valores | Una matriz de ángulos de rotación en grados. |

### Valor de retorno

La instancia del constructor para encadenamiento.

## Observaciones

Este método establece el atributo 'rotate' con múltiples valores, permitiendo la rotación individual de cada carácter o segmento de texto.

### Ver también

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Rotate<TBuilder>(*this TBuilder, double*) {#rotate}

Establece un ángulo de rotación único para todo el contenido de texto.

```csharp
public static TBuilder Rotate<TBuilder>(this TBuilder builder, double value)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | El constructor de elementos SVG. |
| value | El ángulo de rotación en grados. |

### Valor de retorno

La instancia del constructor para encadenamiento.

## Observaciones

Este método establece el atributo 'rotate' con un solo valor, aplicando el mismo ángulo de rotación a todo el contenido de texto.

### Ver también

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
