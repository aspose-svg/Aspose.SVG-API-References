---
title: "SVGBuilderExtensions.LetterSpacing"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método LetterSpacing de SVGBuilderExtensions. Establece el atributo letter-spacing para un elemento SVG usando un valor numérico y un tipo de longitud específico"
type: docs
weight: 1100
url: /es/net/aspose.svg.builder/svgbuilderextensions/letterspacing/
---
## LetterSpacing<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#letterspacing_1}

Establece el atributo 'letter-spacing' para un elemento SVG usando un valor numérico y un tipo de longitud específico.

```csharp
public static TBuilder LetterSpacing<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | La instancia del constructor. |
| value | El valor de espaciado de letras a establecer. |
| type | El tipo de longitud (p. ej., px, em). |

### Valor de retorno

La instancia del constructor para encadenamiento.

### Ver también

* enum [LengthType](../../lengthtype/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## LetterSpacing<TBuilder>(*this TBuilder, [Spacing](../../spacing/)*) {#letterspacing}

Establece el atributo 'letter-spacing' para un elemento SVG usando un valor de espaciado predefinido.

```csharp
public static TBuilder LetterSpacing<TBuilder>(this TBuilder builder, Spacing value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | La instancia del constructor. |
| value | El valor de espaciado predefinido a establecer. |

### Valor de retorno

La instancia del constructor para encadenamiento.

### Ver también

* enum [Spacing](../../spacing/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
