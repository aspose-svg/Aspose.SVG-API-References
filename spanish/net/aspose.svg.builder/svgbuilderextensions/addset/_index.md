---
title: "SVGBuilderExtensions.AddSet"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método AddSet de SVGBuilderExtensions. Añade una configuración de elemento set al constructor"
type: docs
weight: 470
url: /es/net/aspose.svg.builder/svgbuilderextensions/addset/
---
## SVGBuilderExtensions.AddSet<TBuilder> method

Agrega una configuración del elemento 'set' al generador.

```csharp
public static TBuilder AddSet<TBuilder>(this TBuilder builder, 
    Action<SVGSetElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IBaseAnimationElementBuilder
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | La instancia del constructor. |
| configurar | La acción de configuración para el elemento 'set'. |

### Valor de retorno

La instancia del constructor para encadenamiento.

### Ver también

* class [SVGSetElementBuilder](../../svgsetelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IBaseAnimationElementBuilder](../../ibaseanimationelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
