---
title: "SVGBuilderExtensions.AddBuilder"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método SVGBuilderExtensions AddBuilder. Añade un constructor de elemento SVG existente al constructor de elemento SVG actual. Este método se usa para incluir un constructor de elemento SVG predefinido en el constructor actual."
type: docs
weight: 60
url: /es/net/aspose.svg.builder/svgbuilderextensions/addbuilder/
---
## SVGBuilderExtensions.AddBuilder<TBuilder,TElementBuilder> method

Agrega un creador de elementos SVG existente al creador de elementos SVG actual. Este método se utiliza para incluir un creador de elementos SVG predefinido en el creador actual.

```csharp
public static TBuilder AddBuilder<TBuilder, TElementBuilder>(this TBuilder builder, 
    TElementBuilder elementBuilder)
    where TBuilder : ISVGElementBuilder
    where TElementBuilder : ISVGElementBuilder
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| TElementBuilder | El tipo del constructor de elemento SVG que se configurará. TElementBuilder debe implementar ISVGElementBuilder. |
| constructor | El constructor de elemento SVG al que se añade el otro constructor de elemento. |
| elementBuilder | El constructor de elemento SVG que se añadirá. |

### Valor de retorno

El generador de elementos SVG original para encadenamiento de métodos.

### Ver también

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
