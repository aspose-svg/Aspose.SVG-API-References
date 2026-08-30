---
title: "SVGBuilderExtensions.Dx"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método SVGBuilderExtensions Dx. Establece el atributo dx para ajustar la posición horizontal de cada carácter en el texto"
type: docs
weight: 770
url: /es/net/aspose.svg.builder/svgbuilderextensions/dx/
---
## Dx<TBuilder>(*this TBuilder, [LengthType](../../lengthtype/), params double[]*) {#dx}

Establece el atributo 'dx' para ajustar la posición horizontal de cada carácter en el texto.

```csharp
public static TBuilder Dx<TBuilder>(this TBuilder builder, LengthType type = LengthType.Px, 
    params double[] values)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | El constructor de elementos SVG. |
| type | El tipo de unidad de longitud para los valores. |
| valores | Los valores de ajuste horizontal para cada carácter. |

### Valor de retorno

La instancia del constructor para encadenamiento.

## Observaciones

Este método permite un control fino sobre el espaciado horizontal de los caracteres en el texto.

### Ver también

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Dx<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#dx_1}

Establece un único valor de ajuste horizontal para el contenido de texto.

```csharp
public static TBuilder Dx<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, ITextContentPositioningAttributeSetter
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | El constructor de elementos SVG. |
| value | El valor de ajuste horizontal. |
| type | El tipo de unidad de longitud para el valor. |

### Valor de retorno

La instancia del constructor para encadenamiento.

## Observaciones

Este método establece el atributo 'dx' con un solo valor, ajustando la posición horizontal del contenido de texto.

### Ver también

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ITextContentPositioningAttributeSetter](../../itextcontentpositioningattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
